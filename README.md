-- Gui to Lua
-- Version: 3.2

-- Instances:

local StarterGui = Instance.new("ScreenGui")
local Login = Instance.new("Frame")
local Panel = Instance.new("TextLabel")
local Button = Instance.new("ImageLabel")
local LoginButton = Instance.new("TextButton")
local box = Instance.new("ImageLabel")
local Password = Instance.new("TextBox")
local CoolThing = Instance.new("TextLabel")
local main = Instance.new("TextButton")
local Frame10 = Instance.new("Frame")
local Frame2 = Instance.new("Frame")
local EastryEgg = Instance.new("TextButton")
local CosmicEgg = Instance.new("TextButton")
local CrackedEgg = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local Frame3 = Instance.new("Frame")
local Close_2 = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local Jailbreak = Instance.new("TextButton")
local PrisonLife = Instance.new("TextButton")
local Arsenal = Instance.new("TextButton")
local Murder = Instance.new("TextButton")
local TowerOffHell = Instance.new("TextButton")
local BeeSwarmSim = Instance.new("TextButton")
local Bloxburg = Instance.new("TextButton")
local SaberSim = Instance.new("TextButton")
local AntiAfk = Instance.new("TextButton")
local BgsGui = Instance.new("TextButton")
local CloseButton = Instance.new("TextButton")
local FastEgg = Instance.new("TextButton")
local MoreGames = Instance.new("TextButton")
local kenar = Instance.new("ImageLabel")
local kenar_2 = Instance.new("ImageLabel")
local kenar_3 = Instance.new("ImageLabel")
local kenar_4 = Instance.new("ImageLabel")
local Panel_2 = Instance.new("TextLabel")
local Panel_3 = Instance.new("TextLabel")

--Properties:

StarterGui.Name = "StarterGui"
StarterGui.Parent = game.CoreGui

Login.Name = "Login"
Login.Parent = StarterGui
Login.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
Login.BorderSizePixel = 0
Login.Position = UDim2.new(0.416218728, 0, 0.355748773, 0)
Login.Size = UDim2.new(0, 275, 0, 130)

Panel.Name = "Panel"
Panel.Parent = Login
Panel.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Panel.BorderSizePixel = 0
Panel.Size = UDim2.new(0, 275, 0, 22)
Panel.Font = Enum.Font.SourceSans
Panel.Text = "Made by esc community emr#1487"
Panel.TextColor3 = Color3.fromRGB(255, 255, 255)
Panel.TextSize = 18.000

Button.Name = "Button"
Button.Parent = Login
Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Button.BackgroundTransparency = 1.000
Button.Position = UDim2.new(0.0951515138, 0, 0.279887468, 0)
Button.Size = UDim2.new(0, 173, 0, 100)
Button.Image = "rbxassetid://3570695787"
Button.ImageTransparency = 1.000
Button.ScaleType = Enum.ScaleType.Slice
Button.SliceCenter = Rect.new(100, 100, 100, 100)
Button.SliceScale = 0.120

LoginButton.Name = "LoginButton"
LoginButton.Parent = Button
LoginButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LoginButton.BorderSizePixel = 0
LoginButton.Position = UDim2.new(0.288530409, 0, 0.576088071, 0)
LoginButton.Size = UDim2.new(0, 122, 0, 17)
LoginButton.Font = Enum.Font.SourceSans
LoginButton.Text = "Whitelist"
LoginButton.TextColor3 = Color3.fromRGB(0, 0, 0)
LoginButton.TextSize = 14.000

box.Name = "box"
box.Parent = Login
box.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
box.BackgroundTransparency = 1.000
box.Position = UDim2.new(0.0951515138, 0, 0.279887468, 0)
box.Size = UDim2.new(0, 173, 0, 100)
box.Image = "rbxassetid://3570695787"
box.ImageTransparency = 1.000
box.ScaleType = Enum.ScaleType.Slice
box.SliceCenter = Rect.new(100, 100, 100, 100)
box.SliceScale = 0.120

Password.Name = "Password"
Password.Parent = box
Password.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Password.BorderSizePixel = 0
Password.Position = UDim2.new(-0.0938344002, 0, 0.0545374155, 0)
Password.Size = UDim2.new(0, 255, 0, 15)
Password.ClearTextOnFocus = false
Password.Font = Enum.Font.SourceSans
Password.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
Password.PlaceholderText = "Enter Your Key Here"
Password.Text = ""
Password.TextColor3 = Color3.fromRGB(255, 255, 255)
Password.TextSize = 14.000

CoolThing.Name = "CoolThing"
CoolThing.Parent = Login
CoolThing.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CoolThing.Position = UDim2.new(0.0363636352, 0, 0.446153611, 0)
CoolThing.Size = UDim2.new(0, 6, 0, 1)
CoolThing.Font = Enum.Font.SourceSans
CoolThing.Text = ""
CoolThing.TextColor3 = Color3.fromRGB(0, 0, 0)
CoolThing.TextSize = 14.000

main.Name = "main"
main.Parent = StarterGui
main.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
main.BorderSizePixel = 0
main.Position = UDim2.new(0.00727272732, 0, 0.625744939, 0)
main.Size = UDim2.new(0, 200, 0, 50)
main.Visible = false
main.Font = Enum.Font.SourceSans
main.Text = "Open"
main.TextColor3 = Color3.fromRGB(255, 255, 255)
main.TextScaled = true
main.TextSize = 14.000
main.TextWrapped = true

Frame10.Name = "Frame10"
Frame10.Parent = StarterGui
Frame10.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
Frame10.Position = UDim2.new(0.330303073, 0, 0.276519656, 0)
Frame10.Size = UDim2.new(0, 556, 0, 374)
Frame10.Visible = false

Frame2.Name = "Frame2"
Frame2.Parent = Frame10
Frame2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame2.Position = UDim2.new(1.08754492, 0, 0.635370195, 0)
Frame2.Size = UDim2.new(0, 386, 0, 348)
Frame2.Visible = false

EastryEgg.Name = "Eastry Egg"
EastryEgg.Parent = Frame2
EastryEgg.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
EastryEgg.Position = UDim2.new(0.570850968, 0, 0.518579185, 0)
EastryEgg.Size = UDim2.new(0, 139, 0, 99)
EastryEgg.Font = Enum.Font.SourceSans
EastryEgg.Text = "Eastry Egg"
EastryEgg.TextColor3 = Color3.fromRGB(85, 255, 127)
EastryEgg.TextScaled = true
EastryEgg.TextSize = 14.000
EastryEgg.TextWrapped = true
EastryEgg.MouseButton1Down:connect(function()
	_G.OpAutoFarm = true
	while wait() and _G.OpAutoFarm do
		local args = {
			[1] = "PurchaseEgg",
			[2] = "Eastery Egg",
			[3] = "Multi",
		}

		game:GetService("ReplicatedStorage").NetworkRemoteEvent:FireServer(unpack(args))

		local args = {
			[1] = "BlowBubble",
		}

		game:GetService("ReplicatedStorage").NetworkRemoteEvent:FireServer(unpack(args))
	end
	game.StarterGui:SetCore("SendNotification", {
		Title = "Fast Open Egg X2";
		Text = "Made By Esc Comminty emr#1487";
		Duration = 25;
	})
end)

CosmicEgg.Name = "Cosmic Egg"
CosmicEgg.Parent = Frame2
CosmicEgg.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
CosmicEgg.Position = UDim2.new(0.0300124176, 0, 0.520230949, 0)
CosmicEgg.Size = UDim2.new(0, 139, 0, 99)
CosmicEgg.Font = Enum.Font.SourceSans
CosmicEgg.Text = "Cosmic Egg"
CosmicEgg.TextColor3 = Color3.fromRGB(85, 255, 127)
CosmicEgg.TextScaled = true
CosmicEgg.TextSize = 14.000
CosmicEgg.TextWrapped = true
CosmicEgg.MouseButton1Down:connect(function()
	_G.OpAutoFarm = true
	while wait() and _G.OpAutoFarm do
		local args = {
			[1] = "PurchaseEgg",
			[2] = "Cosmic Egg",
			[3] = "Multi",
		}

		game:GetService("ReplicatedStorage").NetworkRemoteEvent:FireServer(unpack(args))

		local args = {
			[1] = "BlowBubble",
		}

		game:GetService("ReplicatedStorage").NetworkRemoteEvent:FireServer(unpack(args))
	end
	game.StarterGui:SetCore("SendNotification", {
		Title = "Fast Open Egg X2";
		Text = "Made By Esc Comminty emr#1487";
		Duration = 25;
	})	
end)

CrackedEgg.Name = "Cracked Egg"
CrackedEgg.Parent = Frame2
CrackedEgg.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
CrackedEgg.Position = UDim2.new(0.293385059, 0, 0.202659905, 0)
CrackedEgg.Size = UDim2.new(0, 139, 0, 99)
CrackedEgg.Font = Enum.Font.SourceSans
CrackedEgg.Text = "Cracked Egg"
CrackedEgg.TextColor3 = Color3.fromRGB(85, 255, 127)
CrackedEgg.TextScaled = true
CrackedEgg.TextSize = 14.000
CrackedEgg.TextWrapped = true
CrackedEgg.MouseButton1Down:connect(function()
	_G.OpAutoFarm = true
	while wait() and _G.OpAutoFarm do
		local args = {
			[1] = "PurchaseEgg",
			[2] = "Cracked Egg",
			[3] = "Multi",
		}

		game:GetService("ReplicatedStorage").NetworkRemoteEvent:FireServer(unpack(args))

		local args = {
			[1] = "BlowBubble",
		}

		game:GetService("ReplicatedStorage").NetworkRemoteEvent:FireServer(unpack(args))
	end
	game.StarterGui:SetCore("SendNotification", {
		Title = "Fast Open Egg X2";
		Text = "Made By Esc Comminty emr#1487";
		Duration = 25;
	})	
end)

Close.Name = "Close"
Close.Parent = Frame2
Close.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Close.Position = UDim2.new(0.851933241, 0, 0.0224257633, 0)
Close.Size = UDim2.new(0, 51, 0, 44)
Close.ZIndex = 2
Close.Font = Enum.Font.SourceSansBold
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(170, 0, 0)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true

TextLabel.Parent = Frame2
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.Position = UDim2.new(0.0310880821, 0, 0.0201149434, 0)
TextLabel.Size = UDim2.new(0, 309, 0, 52)
TextLabel.Font = Enum.Font.SciFi
TextLabel.Text = "BGS NEW UPDATE EASTER 2021"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = Frame2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.Position = UDim2.new(0.0440414511, 0, 0.864942491, 0)
TextLabel_2.Size = UDim2.new(0, 351, 0, 39)
TextLabel_2.Font = Enum.Font.SciFi
TextLabel_2.Text = "made by emr#1487"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

Frame3.Name = "Frame3"
Frame3.Parent = Frame10
Frame3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame3.Position = UDim2.new(1.03358817, 0, -0.452964842, 0)
Frame3.Size = UDim2.new(0, 513, 0, 348)
Frame3.Visible = false

Close_2.Name = "Close"
Close_2.Parent = Frame3
Close_2.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
Close_2.Position = UDim2.new(0.851933241, 0, 0.0224257633, 0)
Close_2.Size = UDim2.new(0, 51, 0, 44)
Close_2.ZIndex = 2
Close_2.Font = Enum.Font.SourceSansBold
Close_2.Text = "X"
Close_2.TextColor3 = Color3.fromRGB(170, 0, 0)
Close_2.TextScaled = true
Close_2.TextSize = 14.000
Close_2.TextWrapped = true

TextLabel_3.Parent = Frame3
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.Position = UDim2.new(0.031088192, 0, 0.0201149434, 0)
TextLabel_3.Size = UDim2.new(0, 390, 0, 52)
TextLabel_3.Font = Enum.Font.SciFi
TextLabel_3.Text = "Games"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

TextLabel_4.Parent = Frame3
TextLabel_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.Position = UDim2.new(0.0440414473, 0, 0.864942551, 0)
TextLabel_4.Size = UDim2.new(0, 478, 0, 39)
TextLabel_4.Font = Enum.Font.SciFi
TextLabel_4.Text = "made by emr#1487"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

Jailbreak.Name = "Jailbreak"
Jailbreak.Parent = Frame3
Jailbreak.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Jailbreak.Position = UDim2.new(0.043872498, 0, 0.245763317, 0)
Jailbreak.Size = UDim2.new(0, 109, 0, 79)
Jailbreak.Font = Enum.Font.SourceSans
Jailbreak.Text = "Jailberak"
Jailbreak.TextColor3 = Color3.fromRGB(85, 255, 127)
Jailbreak.TextScaled = true
Jailbreak.TextSize = 14.000
Jailbreak.TextWrapped = true
Jailbreak.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("https://pastebin.com/rriYhpPQ"),true))()
end)


PrisonLife.Name = "Prison Life"
PrisonLife.Parent = Frame3
PrisonLife.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
PrisonLife.Position = UDim2.new(0.277790636, 0, 0.245763317, 0)
PrisonLife.Size = UDim2.new(0, 109, 0, 79)
PrisonLife.Font = Enum.Font.SourceSans
PrisonLife.Text = "Prison Life"
PrisonLife.TextColor3 = Color3.fromRGB(85, 255, 127)
PrisonLife.TextScaled = true
PrisonLife.TextSize = 14.000
PrisonLife.TextWrapped = true
PrisonLife.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("https://pastebin.com/azhcDd6d"),true))()
end)

Arsenal.Name = "Arsenal"
Arsenal.Parent = Frame3
Arsenal.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Arsenal.Position = UDim2.new(0.527303338, 0, 0.245763317, 0)
Arsenal.Size = UDim2.new(0, 109, 0, 79)
Arsenal.Font = Enum.Font.SourceSans
Arsenal.Text = "Arsenal"
Arsenal.TextColor3 = Color3.fromRGB(85, 255, 127)
Arsenal.TextScaled = true
Arsenal.TextSize = 14.000
Arsenal.TextWrapped = true
Arsenal.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("https://pastebin.com/ctpWehKN"),true))()
end)

Murder.Name = "Murder"
Murder.Parent = Frame3
Murder.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Murder.Position = UDim2.new(0.763170779, 0, 0.245763317, 0)
Murder.Size = UDim2.new(0, 109, 0, 79)
Murder.Font = Enum.Font.SourceSans
Murder.Text = "Mureder Mystry"
Murder.TextColor3 = Color3.fromRGB(85, 255, 127)
Murder.TextScaled = true
Murder.TextSize = 14.000
Murder.TextWrapped = true
Murder.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("https://pastebin.com/XXuX12Nt"),true))()
end)

TowerOffHell.Name = "TowerOffHell"
TowerOffHell.Parent = Frame3
TowerOffHell.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
TowerOffHell.Position = UDim2.new(0.0516697764, 0, 0.564728856, 0)
TowerOffHell.Size = UDim2.new(0, 109, 0, 79)
TowerOffHell.Font = Enum.Font.SourceSans
TowerOffHell.Text = "Tower Off Hell"
TowerOffHell.TextColor3 = Color3.fromRGB(85, 255, 127)
TowerOffHell.TextScaled = true
TowerOffHell.TextSize = 14.000
TowerOffHell.TextWrapped = true
TowerOffHell.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/iiProductionz/Floater-Scripts/main/WaifuEdition/Tower%20Of%20Hell"))()
end)

BeeSwarmSim.Name = "Bee Swarm Sim"
BeeSwarmSim.Parent = Frame3
BeeSwarmSim.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
BeeSwarmSim.Position = UDim2.new(0.293385178, 0, 0.564728856, 0)
BeeSwarmSim.Size = UDim2.new(0, 109, 0, 79)
BeeSwarmSim.Font = Enum.Font.SourceSans
BeeSwarmSim.Text = "Bee Swarm Sim"
BeeSwarmSim.TextColor3 = Color3.fromRGB(85, 255, 127)
BeeSwarmSim.TextScaled = true
BeeSwarmSim.TextSize = 14.000
BeeSwarmSim.TextWrapped = true
BeeSwarmSim.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/iC4VXeXA"))()
end)

Bloxburg.Name = "Bloxburg"
Bloxburg.Parent = Frame3
Bloxburg.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Bloxburg.Position = UDim2.new(0.527303338, 0, 0.564728856, 0)
Bloxburg.Size = UDim2.new(0, 109, 0, 79)
Bloxburg.Font = Enum.Font.SourceSans
Bloxburg.Text = "Bloxburg"
Bloxburg.TextColor3 = Color3.fromRGB(85, 255, 127)
Bloxburg.TextScaled = true
Bloxburg.TextSize = 14.000
Bloxburg.TextWrapped = true
Bloxburg.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/5ZyXEkBF"))()
end)

SaberSim.Name = "Saber Sim"
SaberSim.Parent = Frame3
SaberSim.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
SaberSim.Position = UDim2.new(0.763170779, 0, 0.564728856, 0)
SaberSim.Size = UDim2.new(0, 109, 0, 79)
SaberSim.Font = Enum.Font.SourceSans
SaberSim.Text = "Saber sim"
SaberSim.TextColor3 = Color3.fromRGB(85, 255, 127)
SaberSim.TextScaled = true
SaberSim.TextSize = 14.000
SaberSim.TextWrapped = true
SaberSim.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://gist.githubusercontent.com/MincraftGamerYTPRO/4856a0e840f31f16767df1537465b14f/raw/c5494726d554649ac3e0fc6f5870be393a344f66/gistfile1.txt"))()
end)

AntiAfk.Name = "AntiAfk"
AntiAfk.Parent = Frame10
AntiAfk.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
AntiAfk.Position = UDim2.new(0.0404758602, 0, 0.219633222, 0)
AntiAfk.Size = UDim2.new(0, 145, 0, 128)
AntiAfk.Font = Enum.Font.SourceSans
AntiAfk.Text = "Anti Afk"
AntiAfk.TextColor3 = Color3.fromRGB(0, 0, 0)
AntiAfk.TextScaled = true
AntiAfk.TextSize = 14.000
AntiAfk.TextWrapped = true
AntiAfk.MouseButton1Down:connect(function()
	wait(0.5)local ba=Instance.new("ScreenGui")
	local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
	local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
	ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
	ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
	ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,304,0,52)
	ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti Afk"ca.TextColor3=Color3.new(0,1,1)
	ca.TextSize=22;da.Parent=ca
	da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
	da.Size=UDim2.new(0,304,0,107)_b.Parent=da
	_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
	_b.Size=UDim2.new(0,304,0,21)_b.Font=Enum.Font.Arial;_b.Text="Made by Esc"
	_b.TextColor3=Color3.new(1,1,1)_b.TextSize=20;ab.Parent=da
	ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377379,0)
	ab.Size=UDim2.new(0,304,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Durum:Hıle Aktıf"
	ab.TextColor3=Color3.new(1,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
	game:service'Players'.LocalPlayer.Idled:connect(function()
		bb:CaptureController()bb:ClickButton2(Vector2.new())
		ab.Text="Roblox Senı Oyundan Atmaya Calstı Ama Olmadı"wait(150)ab.Text="Hıle Baslaıldı"end)
end)

BgsGui.Name = "BgsGui"
BgsGui.Parent = Frame10
BgsGui.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
BgsGui.Position = UDim2.new(0.375963956, 0, 0.219994754, 0)
BgsGui.Size = UDim2.new(0, 145, 0, 128)
BgsGui.Font = Enum.Font.SourceSansBold
BgsGui.Text = "Bubble Gum Simulator"
BgsGui.TextColor3 = Color3.fromRGB(0, 0, 0)
BgsGui.TextScaled = true
BgsGui.TextSize = 14.000
BgsGui.TextWrapped = true
BgsGui.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("http://roguefamily.com/script/streleziaBGSbeta/script"),true))()
end)

CloseButton.Name = "CloseButton"
CloseButton.Parent = Frame10
CloseButton.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
CloseButton.BorderSizePixel = 0
CloseButton.Position = UDim2.new(0.911192298, 0, 0.0199346915, 0)
CloseButton.Size = UDim2.new(0, 37, 0, 36)
CloseButton.Font = Enum.Font.SourceSans
CloseButton.Text = "Close"
CloseButton.TextColor3 = Color3.fromRGB(0, 0, 0)
CloseButton.TextScaled = true
CloseButton.TextSize = 14.000
CloseButton.TextWrapped = true

FastEgg.Name = "Fast Egg"
FastEgg.Parent = Frame10
FastEgg.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
FastEgg.Position = UDim2.new(0.697983563, 0, 0.219994754, 0)
FastEgg.Size = UDim2.new(0, 145, 0, 128)
FastEgg.Font = Enum.Font.SourceSans
FastEgg.Text = "Fast Egg"
FastEgg.TextColor3 = Color3.fromRGB(0, 0, 0)
FastEgg.TextScaled = true
FastEgg.TextSize = 14.000
FastEgg.TextWrapped = true

MoreGames.Name = "MoreGames"
MoreGames.Parent = Frame10
MoreGames.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
MoreGames.Position = UDim2.new(0.0685834289, 0, 0.614639938, 0)
MoreGames.Size = UDim2.new(0, 485, 0, 76)
MoreGames.Font = Enum.Font.SourceSans
MoreGames.Text = "More Games"
MoreGames.TextColor3 = Color3.fromRGB(0, 0, 0)
MoreGames.TextScaled = true
MoreGames.TextSize = 14.000
MoreGames.TextWrapped = true

kenar.Name = "kenar"
kenar.Parent = Frame10
kenar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
kenar.BackgroundTransparency = 1.000
kenar.BorderColor3 = Color3.fromRGB(27, 42, 53)
kenar.Position = UDim2.new(0.987231731, 0, -0.0214715991, 0)
kenar.Size = UDim2.new(0, 13, 0, 382)
kenar.Image = "rbxassetid://3570695787"
kenar.ImageColor3 = Color3.fromRGB(40, 40, 40)
kenar.ScaleType = Enum.ScaleType.Slice
kenar.SliceCenter = Rect.new(100, 100, 100, 100)
kenar.SliceScale = 0.120

kenar_2.Name = "kenar"
kenar_2.Parent = Frame10
kenar_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
kenar_2.BackgroundTransparency = 1.000
kenar_2.BorderColor3 = Color3.fromRGB(27, 42, 53)
kenar_2.Position = UDim2.new(-0.0173018239, 0, -0.0214715991, 0)
kenar_2.Size = UDim2.new(0, 13, 0, 382)
kenar_2.Image = "rbxassetid://3570695787"
kenar_2.ImageColor3 = Color3.fromRGB(40, 40, 40)
kenar_2.ScaleType = Enum.ScaleType.Slice
kenar_2.SliceCenter = Rect.new(100, 100, 100, 100)
kenar_2.SliceScale = 0.120

kenar_3.Name = "kenar"
kenar_3.Parent = Frame10
kenar_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
kenar_3.BackgroundTransparency = 1.000
kenar_3.BorderColor3 = Color3.fromRGB(27, 42, 53)
kenar_3.Position = UDim2.new(-0.017301878, 0, 0.966399312, 0)
kenar_3.Size = UDim2.new(0, 573, 0, 11)
kenar_3.Image = "rbxassetid://3570695787"
kenar_3.ImageColor3 = Color3.fromRGB(40, 40, 40)
kenar_3.ScaleType = Enum.ScaleType.Slice
kenar_3.SliceCenter = Rect.new(100, 100, 100, 100)
kenar_3.SliceScale = 0.120

kenar_4.Name = "kenar"
kenar_4.Parent = Frame10
kenar_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
kenar_4.BackgroundTransparency = 1.000
kenar_4.BorderColor3 = Color3.fromRGB(27, 42, 53)
kenar_4.Position = UDim2.new(-0.0173018239, 0, -0.0214715786, 0)
kenar_4.Size = UDim2.new(0, 571, 0, 11)
kenar_4.Image = "rbxassetid://3570695787"
kenar_4.ImageColor3 = Color3.fromRGB(40, 40, 40)
kenar_4.ScaleType = Enum.ScaleType.Slice
kenar_4.SliceCenter = Rect.new(100, 100, 100, 100)
kenar_4.SliceScale = 0.120

Panel_2.Name = "Panel"
Panel_2.Parent = Frame10
Panel_2.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Panel_2.BackgroundTransparency = 1.000
Panel_2.BorderSizePixel = 0
Panel_2.Position = UDim2.new(0.154336274, 0, 0.0195430908, 0)
Panel_2.Size = UDim2.new(0, 384, 0, 28)
Panel_2.Font = Enum.Font.SourceSans
Panel_2.Text = "Made by esc community emr#1487"
Panel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Panel_2.TextScaled = true
Panel_2.TextSize = 18.000
Panel_2.TextWrapped = true

Panel_3.Name = "Panel"
Panel_3.Parent = Frame10
Panel_3.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Panel_3.BackgroundTransparency = 1.000
Panel_3.BorderSizePixel = 0
Panel_3.Position = UDim2.new(0.00918573607, 0, 0.890801847, 0)
Panel_3.Size = UDim2.new(0, 543, 0, 28)
Panel_3.Font = Enum.Font.SourceSans
Panel_3.Text = "Made by esc community emr#1487"
Panel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Panel_3.TextScaled = true
Panel_3.TextSize = 18.000
Panel_3.TextWrapped = true

-- Scripts:

local function XZZKGYC_fake_script() -- LoginButton.LocalScript 
	local script = Instance.new('LocalScript', LoginButton)

	local password = script.Parent.Parent.Parent.box.Password
	local main = script.Parent.Parent.Parent.Parent.main
	local login = script.Parent.Parent.Parent.Parent.Login
	
	main.Visible = false
	
	script.Parent.MouseButton1Click:Connect(function()
		if password.Text == "emresc" or 
			password.Text == "emresc2" then
			login.Visible = false
			main.Visible = true
	
	
			
		end
	end)
end
coroutine.wrap(XZZKGYC_fake_script)()
local function EQFSXN_fake_script() -- main.LocalScript 
	local script = Instance.new('LocalScript', main)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Frame10.Visible = true
	end)
end
coroutine.wrap(EQFSXN_fake_script)()
local function ENCXFL_fake_script() -- Frame10.LocalScript 
	local script = Instance.new('LocalScript', Frame10)

	script.Parent.Selectable = true
	script.Parent.Active = true
	script.Parent.Draggable = true 
end
coroutine.wrap(ENCXFL_fake_script)()
local function PPQSPB_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(PPQSPB_fake_script)()
local function OMIQDE_fake_script() -- Frame2.LocalScript 
	local script = Instance.new('LocalScript', Frame2)

	script.Parent.Selectable = true
	script.Parent.Active = true
	script.Parent.Draggable = true 
end
coroutine.wrap(OMIQDE_fake_script)()
local function NCVGUF_fake_script() -- Close_2.LocalScript 
	local script = Instance.new('LocalScript', Close_2)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(NCVGUF_fake_script)()
local function BKCZAM_fake_script() -- Frame3.LocalScript 
	local script = Instance.new('LocalScript', Frame3)

	script.Parent.Selectable = true
	script.Parent.Active = true
	script.Parent.Draggable = true 
end
coroutine.wrap(BKCZAM_fake_script)()
local function KKJOWAI_fake_script() -- CloseButton.LocalScript 
	local script = Instance.new('LocalScript', CloseButton)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(KKJOWAI_fake_script)()
local function SJRNHNB_fake_script() -- FastEgg.LocalScript 
	local script = Instance.new('LocalScript', FastEgg)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Frame2.Visible = true
	end)
end
coroutine.wrap(SJRNHNB_fake_script)()
local function DDQZO_fake_script() -- MoreGames.LocalScript 
	local script = Instance.new('LocalScript', MoreGames)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.Frame3.Visible = true
	end)
end
coroutine.wrap(DDQZO_fake_script)()
