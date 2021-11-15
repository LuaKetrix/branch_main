# branch_main
(Roblox Lua aka Lua u)
--lesson - table.find()


local thing2 = "thing2"-- just a variable
local Table = {-- our table 
	"thing1";
	"thing2";--this is the value we will find with table.find()
	"thing3";
}
--table.find(Table,thing2)--sense our variable we set call thing2 is a string
--called thing2 it will look through the table, if that string value is
--the same value that is in the table
if table.find(Table,thing2) then--we do an if statement to check if that value is in the table
	print("Found thing2 in the table named, Table")
end
--this could also be useful for a admins list for example:
local Admins = {--the admins
	--id1
	--id2
	--id3
}--I reccomend going by the id because the user could change their username
if table.find(Admins,p.UserId) then--this could be used in a local script to check if a player is a admin or not
	
end
