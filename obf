local toByte = [[StringHere]]
local bytes = {}
local stringValue = Instance.new('StringValue', game)
stringValue.Name = 'byteValue'

function run()
	for i = 0,toByte:len() do
		local byteForm = toByte:byte(i)
		table.insert(bytes, byteForm)
	end
end

function compile()
	for i,v in pairs(bytes) do
		stringValue.Value = stringValue.Value..v.." "
	end
end

spawn(run)
spawn(compile)
