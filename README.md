-- Ultimate Gui

--Version 1.0.0

local UltimateGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")
local TowerOfHellTitle = Instance.new("TextLabel")
local AdoptMeTitle = Instance.new("TextLabel")
local MurderMysteryTitle = Instance.new("TextLabel")
local BloxburgTitle = Instance.new("TextLabel")
local PetSimXTitle = Instance.new("TextLabel")
local DaHoodTitle = Instance.new("TextLabel")
local AutoFarm = Instance.new("TextButton")
local RayCodeX = Instance.new("TextButton")
local RayCodeXCashDropper = Instance.new("TextButton")
local PetSimX2 = Instance.new("TextButton")
local PetSimX1 = Instance.new("TextButton")
local PetSimX1_2 = Instance.new("TextButton")
local MurderMystery = Instance.new("TextButton")
local VGHub = Instance.new("TextButton")
local TowerOfHell = Instance.new("TextButton")

--Properties:

UltimateGui.Name = "UltimateGui"
UltimateGui.Parent = game.CoreGui
UltimateGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = UltimateGui
Main.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
Main.Position = UDim2.new(0.301464915, 0, 0.247852758, 0)
Main.Size = UDim2.new(0, 514, 0, 410)
Main.Draggable = true

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 85, 255)
TextLabel.Size = UDim2.new(0, 514, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Ultimate Gui"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = Main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.389105052, 0, 1, 0)
TextLabel_2.Size = UDim2.new(0, 114, 0, 30)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Version: 1.0.0"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

TextLabel_3.Parent = Main
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 85, 255)
TextLabel_3.Position = UDim2.new(0, 0, 0.878048778, 0)
TextLabel_3.Size = UDim2.new(0, 514, 0, 50)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Made By RubyBoo4life"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

ScrollingFrame.Parent = Main
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(0, 85, 255)
ScrollingFrame.Position = UDim2.new(0.0165752172, 0, 0.139742628, 0)
ScrollingFrame.Size = UDim2.new(0, 496, 0, 295)

TowerOfHellTitle.Name = "TowerOfHellTitle"
TowerOfHellTitle.Parent = ScrollingFrame
TowerOfHellTitle.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
TowerOfHellTitle.Position = UDim2.new(0, 0, 0.813893437, 0)
TowerOfHellTitle.Size = UDim2.new(0, 483, 0, 50)
TowerOfHellTitle.Font = Enum.Font.SourceSans
TowerOfHellTitle.Text = "Tower Of Hell"
TowerOfHellTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
TowerOfHellTitle.TextScaled = true
TowerOfHellTitle.TextSize = 14.000
TowerOfHellTitle.TextWrapped = true

AdoptMeTitle.Name = "AdoptMeTitle"
AdoptMeTitle.Parent = ScrollingFrame
AdoptMeTitle.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
AdoptMeTitle.Position = UDim2.new(0, 0, 0.665733933, 0)
AdoptMeTitle.Size = UDim2.new(0, 483, 0, 50)
AdoptMeTitle.Font = Enum.Font.SourceSans
AdoptMeTitle.Text = "Adopt Me"
AdoptMeTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
AdoptMeTitle.TextScaled = true
AdoptMeTitle.TextSize = 14.000
AdoptMeTitle.TextWrapped = true

MurderMysteryTitle.Name = "MurderMysteryTitle"
MurderMysteryTitle.Parent = ScrollingFrame
MurderMysteryTitle.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
MurderMysteryTitle.Position = UDim2.new(0, 0, 0.504833162, 0)
MurderMysteryTitle.Size = UDim2.new(0, 483, 0, 50)
MurderMysteryTitle.Font = Enum.Font.SourceSans
MurderMysteryTitle.Text = "Murder Mystery"
MurderMysteryTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
MurderMysteryTitle.TextScaled = true
MurderMysteryTitle.TextSize = 14.000
MurderMysteryTitle.TextWrapped = true

BloxburgTitle.Name = "BloxburgTitle"
BloxburgTitle.Parent = ScrollingFrame
BloxburgTitle.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
BloxburgTitle.Position = UDim2.new(0, 0, 0.344538391, 0)
BloxburgTitle.Size = UDim2.new(0, 483, 0, 50)
BloxburgTitle.Font = Enum.Font.SourceSans
BloxburgTitle.Text = "BloxBurg"
BloxburgTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
BloxburgTitle.TextScaled = true
BloxburgTitle.TextSize = 14.000
BloxburgTitle.TextWrapped = true

PetSimXTitle.Name = "PetSimXTitle"
PetSimXTitle.Parent = ScrollingFrame
PetSimXTitle.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
PetSimXTitle.Position = UDim2.new(0, 0, 0.19284752, 0)
PetSimXTitle.Size = UDim2.new(0, 483, 0, 50)
PetSimXTitle.Font = Enum.Font.SourceSans
PetSimXTitle.Text = "Pet Simulator X"
PetSimXTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
PetSimXTitle.TextScaled = true
PetSimXTitle.TextSize = 14.000
PetSimXTitle.TextWrapped = true

DaHoodTitle.Name = "DaHoodTitle"
DaHoodTitle.Parent = ScrollingFrame
DaHoodTitle.BackgroundColor3 = Color3.fromRGB(84, 92, 255)
DaHoodTitle.Size = UDim2.new(0, 483, 0, 50)
DaHoodTitle.Font = Enum.Font.SourceSans
DaHoodTitle.Text = "Da Hood"
DaHoodTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
DaHoodTitle.TextScaled = true
DaHoodTitle.TextSize = 14.000
DaHoodTitle.TextWrapped = true

AutoFarm.Name = "AutoFarm"
AutoFarm.Parent = ScrollingFrame
AutoFarm.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
AutoFarm.Position = UDim2.new(0.551415205, 0, 0.0616579726, 0)
AutoFarm.Size = UDim2.new(0, 200, 0, 50)
AutoFarm.Font = Enum.Font.SourceSans
AutoFarm.Text = "Auto Farm"
AutoFarm.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoFarm.TextScaled = true
AutoFarm.TextSize = 14.000
AutoFarm.TextWrapped = true
AutoFarm.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/rapnz/scripts/master/DaHoodFarm.lua"))()
end)

RayCodeX.Name = "RayCodeX"
RayCodeX.Parent = ScrollingFrame
RayCodeX.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
RayCodeX.Position = UDim2.new(0.0171410143, 0, 0.0604064018, 0)
RayCodeX.Size = UDim2.new(0, 200, 0, 50)
RayCodeX.Font = Enum.Font.SourceSans
RayCodeX.Text = "RAYCODEX"
RayCodeX.TextColor3 = Color3.fromRGB(255, 255, 255)
RayCodeX.TextScaled = true
RayCodeX.TextSize = 14.000
RayCodeX.TextWrapped = true
RayCodeX.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://5812737894")[1].Source)()
end)

RayCodeXCashDropper.Name = "RayCodeXCashDropper"
RayCodeXCashDropper.Parent = ScrollingFrame
RayCodeXCashDropper.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
RayCodeXCashDropper.Position = UDim2.new(0.297382951, 0, 0.122761875, 0)
RayCodeXCashDropper.Size = UDim2.new(0, 200, 0, 50)
RayCodeXCashDropper.Font = Enum.Font.SourceSans
RayCodeXCashDropper.Text = "RAYCODEX Cash Dropper"
RayCodeXCashDropper.TextColor3 = Color3.fromRGB(255, 255, 255)
RayCodeXCashDropper.TextScaled = true
RayCodeXCashDropper.TextSize = 14.000
RayCodeXCashDropper.TextWrapped = true
RayCodeXCashDropper.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("https://raw.githubusercontent.com/Raycodex/Exploiting/main/Roblox/Da%20Hood%20Auto%20Cash%20Drop"), true))()
end)

PetSimX2.Name = "PetSimX2"
PetSimX2.Parent = ScrollingFrame
PetSimX2.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
PetSimX2.Position = UDim2.new(0.551415205, 0, 0.264719069, 0)
PetSimX2.Size = UDim2.new(0, 200, 0, 50)
PetSimX2.Font = Enum.Font.SourceSans
PetSimX2.Text = "Pet Simulator X 2"
PetSimX2.TextColor3 = Color3.fromRGB(255, 255, 255)
PetSimX2.TextScaled = true
PetSimX2.TextSize = 14.000
PetSimX2.TextWrapped = true
PetSimX2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://system-exodus.com/scripts/PetSimulator/PetSimulatorX.lua", true))()
end)

PetSimX1.Name = "PetSimX1"
PetSimX1.Parent = ScrollingFrame
PetSimX1.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
PetSimX1.Position = UDim2.new(0.0171410143, 0, 0.264813095, 0)
PetSimX1.Size = UDim2.new(0, 200, 0, 50)
PetSimX1.Font = Enum.Font.SourceSans
PetSimX1.Text = "Pet Simulator X 1"
PetSimX1.TextColor3 = Color3.fromRGB(255, 255, 255)
PetSimX1.TextScaled = true
PetSimX1.TextSize = 14.000
PetSimX1.TextWrapped = true
PetSimX1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/95HthyJq"))()
end)

PetSimX1_2.Name = "PetSimX1"
PetSimX1_2.Parent = ScrollingFrame
PetSimX1_2.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
PetSimX1_2.Position = UDim2.new(0.299399078, 0, 0.423890531, 0)
PetSimX1_2.Size = UDim2.new(0, 200, 0, 50)
PetSimX1_2.Font = Enum.Font.SourceSans
PetSimX1_2.Text = "Hair Dresser autofarm"
PetSimX1_2.TextColor3 = Color3.fromRGB(255, 255, 255)
PetSimX1_2.TextScaled = true
PetSimX1_2.TextSize = 14.000
PetSimX1_2.TextWrapped = true
PetSimX1_2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Introvert1337/Releases/master/bloxburghairfarm.lua"))()
end)

MurderMystery.Name = "MurderMystery"
MurderMystery.Parent = ScrollingFrame
MurderMystery.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
MurderMystery.Position = UDim2.new(0.299399078, 0, 0.585412264, 0)
MurderMystery.Size = UDim2.new(0, 200, 0, 50)
MurderMystery.Font = Enum.Font.SourceSans
MurderMystery.Text = "Vynixu's MM2 Script"
MurderMystery.TextColor3 = Color3.fromRGB(255, 255, 255)
MurderMystery.TextScaled = true
MurderMystery.TextSize = 14.000
MurderMystery.TextWrapped = true
MurderMystery.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()

	-- Made by Vynixu with love ;)
	-- lol enjoy
end)

VGHub.Name = "VGHub"
VGHub.Parent = ScrollingFrame
VGHub.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
VGHub.Position = UDim2.new(0.299399078, 0, 0.742070973, 0)
VGHub.Size = UDim2.new(0, 200, 0, 50)
VGHub.Font = Enum.Font.SourceSans
VGHub.Text = "V.G Hub"
VGHub.TextColor3 = Color3.fromRGB(255, 255, 255)
VGHub.TextScaled = true
VGHub.TextSize = 14.000
VGHub.TextWrapped = true
VGHub.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
end)

TowerOfHell.Name = "TowerOfHell"
TowerOfHell.Parent = ScrollingFrame
TowerOfHell.BackgroundColor3 = Color3.fromRGB(102, 64, 255)
TowerOfHell.Position = UDim2.new(0.299399078, 0, 0.893821776, 0)
TowerOfHell.Size = UDim2.new(0, 200, 0, 50)
TowerOfHell.Font = Enum.Font.SourceSans
TowerOfHell.Text = "GHUB  FREE"
TowerOfHell.TextColor3 = Color3.fromRGB(255, 255, 255)
TowerOfHell.TextScaled = true
TowerOfHell.TextSize = 14.000
TowerOfHell.TextWrapped = true
TowerOfHell.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/2dgeneralspam1/scripts-and-stuff/master/scripts/garfield%20hub", true))()

end)
