-- Gui to Lua
-- Version: 3.2

-- Instances:

local ywelhScreen = Instance.new("ScreenGui")
local ywelhFrame = Instance.new("Frame")
local ywelhUIGradient = Instance.new("UIGradient")
local swagmode = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local drivingsimulator = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local adoptme = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local mm2 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local owlhub = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local infiniteyield = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local fatesadmin = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local bighead = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local Disocrd = Instance.new("TextLabel")
local UIGradient = Instance.new("UIGradient")
local ywelhtitle = Instance.new("TextLabel")
local UIGradient_2 = Instance.new("UIGradient")
local TextButton = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local openfarm = Instance.new("Frame")
local ywelhopen = Instance.new("TextButton")
local UIGradient_3 = Instance.new("UIGradient")
local UICorner_10 = Instance.new("UICorner")

--Properties:

ywelhScreen.Name = "ywelhScreen"
ywelhScreen.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ywelhScreen.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ywelhScreen.Parent = game.CoreGui

ywelhFrame.Name = "ywelhFrame"
ywelhFrame.Parent = ywelhScreen
ywelhFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ywelhFrame.Position = UDim2.new(0.244897649, 0, 0.131886482, 0)
ywelhFrame.Size = UDim2.new(0, 783, 0, 441)
ywelhFrame.Visible = false
ywelhFrame.Draggable = true


ywelhUIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 3, 3)), ColorSequenceKeypoint.new(0.48, Color3.fromRGB(128, 1, 1)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
ywelhUIGradient.Name = "ywelhUIGradient"
ywelhUIGradient.Parent = ywelhFrame

swagmode.Name = "swagmode"
swagmode.Parent = ywelhFrame
swagmode.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
swagmode.BorderColor3 = Color3.fromRGB(0, 0, 0)
swagmode.Position = UDim2.new(0.0268199239, 0, 0.18820861, 0)
swagmode.Size = UDim2.new(0, 200, 0, 50)
swagmode.Font = Enum.Font.SourceSans
swagmode.Text = "Swagmode"
swagmode.TextColor3 = Color3.fromRGB(0, 0, 0)
swagmode.TextScaled = true
swagmode.TextSize = 14.000
swagmode.TextWrapped = true
swagmode.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/lerkermer/lua-projects/master/SwagModeV002"))()
end)

UICorner.CornerRadius = UDim.new(1, 0)
UICorner.Parent = swagmode

drivingsimulator.Name = "drivingsimulator"
drivingsimulator.Parent = ywelhFrame
drivingsimulator.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
drivingsimulator.BorderColor3 = Color3.fromRGB(0, 0, 0)
drivingsimulator.Position = UDim2.new(0.358876109, 0, 0.18820861, 0)
drivingsimulator.Size = UDim2.new(0, 200, 0, 50)
drivingsimulator.Font = Enum.Font.SourceSans
drivingsimulator.Text = "Driving Simulator"
drivingsimulator.TextColor3 = Color3.fromRGB(0, 0, 0)
drivingsimulator.TextScaled = true
drivingsimulator.TextSize = 14.000
drivingsimulator.TextWrapped = true
drivingsimulator.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/vzffWTq4", true))()
end)

UICorner_2.CornerRadius = UDim.new(1, 0)
UICorner_2.Parent = drivingsimulator

adoptme.Name = "adoptme"
adoptme.Parent = ywelhFrame
adoptme.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
adoptme.BorderColor3 = Color3.fromRGB(0, 0, 0)
adoptme.Position = UDim2.new(0.0268199239, 0, 0.650793672, 0)
adoptme.Size = UDim2.new(0, 200, 0, 50)
adoptme.Font = Enum.Font.SourceSans
adoptme.Text = "Adopt Me"
adoptme.TextColor3 = Color3.fromRGB(0, 0, 0)
adoptme.TextScaled = true
adoptme.TextSize = 14.000
adoptme.TextWrapped = true
adoptme.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/Z3iAXASr", true))()
end)

UICorner_3.CornerRadius = UDim.new(1, 0)
UICorner_3.Parent = adoptme

mm2.Name = "mm2"
mm2.Parent = ywelhFrame
mm2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
mm2.BorderColor3 = Color3.fromRGB(0, 0, 0)
mm2.Position = UDim2.new(0.706257999, 0, 0.18820861, 0)
mm2.Size = UDim2.new(0, 200, 0, 50)
mm2.Font = Enum.Font.SourceSans
mm2.Text = "Mm2"
mm2.TextColor3 = Color3.fromRGB(0, 0, 0)
mm2.TextScaled = true
mm2.TextSize = 14.000
mm2.TextWrapped = true
mm2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Doggo-cryto/EclipseMM2/master/Script", true))()
end)

UICorner_4.CornerRadius = UDim.new(1, 0)
UICorner_4.Parent = mm2

owlhub.Name = "owlhub"
owlhub.Parent = ywelhFrame
owlhub.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
owlhub.BorderColor3 = Color3.fromRGB(0, 0, 0)
owlhub.Position = UDim2.new(0.358876109, 0, 0.650793672, 0)
owlhub.Size = UDim2.new(0, 200, 0, 50)
owlhub.Font = Enum.Font.SourceSans
owlhub.Text = "Owl Hub"
owlhub.TextColor3 = Color3.fromRGB(0, 0, 0)
owlhub.TextScaled = true
owlhub.TextSize = 14.000
owlhub.TextWrapped = true
owlhub.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
end)

UICorner_5.CornerRadius = UDim.new(1, 0)
UICorner_5.Parent = owlhub

infiniteyield.Name = "infiniteyield"
infiniteyield.Parent = ywelhFrame
infiniteyield.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
infiniteyield.BorderColor3 = Color3.fromRGB(0, 0, 0)
infiniteyield.Position = UDim2.new(0.158365265, 0, 0.408163249, 0)
infiniteyield.Size = UDim2.new(0, 200, 0, 50)
infiniteyield.Font = Enum.Font.SourceSans
infiniteyield.Text = "InfAlt"
infiniteyield.TextColor3 = Color3.fromRGB(0, 0, 0)
infiniteyield.TextScaled = true
infiniteyield.TextSize = 14.000
infiniteyield.TextWrapped = true
infiniteyield.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

UICorner_6.CornerRadius = UDim.new(1, 0)
UICorner_6.Parent = infiniteyield

fatesadmin.Name = "fatesadmin"
fatesadmin.Parent = ywelhFrame
fatesadmin.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
fatesadmin.BorderColor3 = Color3.fromRGB(0, 0, 0)
fatesadmin.Position = UDim2.new(0.706257999, 0, 0.650793672, 0)
fatesadmin.Size = UDim2.new(0, 200, 0, 50)
fatesadmin.Font = Enum.Font.SourceSans
fatesadmin.Text = "Fates Admin"
fatesadmin.TextColor3 = Color3.fromRGB(0, 0, 0)
fatesadmin.TextScaled = true
fatesadmin.TextSize = 14.000
fatesadmin.TextWrapped = true
fatesadmin.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))();
end)

UICorner_7.CornerRadius = UDim.new(1, 0)
UICorner_7.Parent = fatesadmin

bighead.Name = "bighead"
bighead.Parent = ywelhFrame
bighead.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
bighead.BorderColor3 = Color3.fromRGB(0, 0, 0)
bighead.Position = UDim2.new(0.540229917, 0, 0.408163249, 0)
bighead.Size = UDim2.new(0, 200, 0, 50)
bighead.Font = Enum.Font.SourceSans
bighead.Text = "BigHead"
bighead.TextColor3 = Color3.fromRGB(0, 0, 0)
bighead.TextScaled = true
bighead.TextSize = 14.000
bighead.TextWrapped = true
bighead.MouseButton1Down:connect(function()
	--Shit ass script made by failedmite57926

	local LocalPlayer = game:GetService("Players").LocalPlayer
	local Character = LocalPlayer.Character
	local Humanoid = Character:FindFirstChildOfClass("Humanoid")

	function rm()
		for i,v in pairs(Character:GetDescendants()) do
			if v:IsA("BasePart") then
				if v.Name == "Handle" or v.Name == "Head" then
					if Character.Head:FindFirstChild("OriginalSize") then
						Character.Head.OriginalSize:Destroy()
					end
				else
					for i,cav in pairs(v:GetDescendants()) do
						if cav:IsA("Attachment") then
							if cav:FindFirstChild("OriginalPosition") then
								cav.OriginalPosition:Destroy()
							end
						end
					end
					v:FindFirstChild("OriginalSize"):Destroy()
					if v:FindFirstChild("AvatarPartScaleType") then
						v:FindFirstChild("AvatarPartScaleType"):Destroy()
					end
				end
			end
		end
	end

	rm()
	wait(0.5)
	Humanoid:FindFirstChild("BodyProportionScale"):Destroy()
	wait(1)

	rm()
	wait(0.5)
	Humanoid:FindFirstChild("BodyHeightScale"):Destroy()
	wait(1)

	rm()
	wait(0.5)
	Humanoid:FindFirstChild("BodyWidthScale"):Destroy()
	wait(1)

	rm()
	wait(0.5)
	Humanoid:FindFirstChild("BodyDepthScale"):Destroy()
	wait(1)

	rm()
	wait(0.5)
	Humanoid:FindFirstChild("HeadScale"):Destroy()
	wait(1)
end)

UICorner_8.CornerRadius = UDim.new(1, 0)
UICorner_8.Parent = bighead

Disocrd.Name = "Disocrd"
Disocrd.Parent = ywelhFrame
Disocrd.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Disocrd.Position = UDim2.new(0, 0, 0.891156435, 0)
Disocrd.Size = UDim2.new(0, 783, 0, 48)
Disocrd.Font = Enum.Font.SourceSans
Disocrd.Text = "https://discord.gg/rlar"
Disocrd.TextColor3 = Color3.fromRGB(0, 0, 0)
Disocrd.TextScaled = true
Disocrd.TextSize = 14.000
Disocrd.TextWrapped = true
Disocrd.Draggable = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient.Parent = Disocrd

ywelhtitle.Name = "ywelhtitle"
ywelhtitle.Parent = ywelhFrame
ywelhtitle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ywelhtitle.Size = UDim2.new(0, 783, 0, 54)
ywelhtitle.Font = Enum.Font.SourceSans
ywelhtitle.Text = "Ywelh"
ywelhtitle.TextColor3 = Color3.fromRGB(17, 17, 17)
ywelhtitle.TextScaled = true
ywelhtitle.TextSize = 14.000
ywelhtitle.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
ywelhtitle.TextWrapped = true
ywelhtitle.Draggable = true


UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(0.42, Color3.fromRGB(145, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_2.Parent = ywelhtitle

TextButton.Parent = ywelhtitle
TextButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextButton.Position = UDim2.new(0.918263078, 0, 0, 0)
TextButton.Size = UDim2.new(0, 64, 0, 54)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "X"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true
TextButton.MouseButton1Down:connect(function()
	openfarm.Visible = true
	ywelhFrame.Visible = false
end)


UICorner_9.Parent = TextButton

openfarm.Name = "openfarm"
openfarm.Parent = ywelhScreen
openfarm.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
openfarm.BackgroundTransparency = 1.000
openfarm.Position = UDim2.new(0.00394944707, 0, 0.252086818, 0)
openfarm.Size = UDim2.new(0, 100, 0, 100)

ywelhopen.Name = "ywelhopen"
ywelhopen.Parent = openfarm
ywelhopen.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
ywelhopen.Position = UDim2.new(-0.0501369275, 0, 1.69751191, 0)
ywelhopen.Size = UDim2.new(0, 106, 0, 36)
ywelhopen.Font = Enum.Font.SourceSans
ywelhopen.Text = "Open "
ywelhopen.TextColor3 = Color3.fromRGB(0, 0, 0)
ywelhopen.TextSize = 14.000
ywelhopen.MouseButton1Down:connect(function()
	ywelhFrame.Visible = true
	openfarm.Visible = false
end)

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(0.68, Color3.fromRGB(90, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient_3.Parent = ywelhopen

UICorner_10.CornerRadius = UDim.new(0, 7)
UICorner_10.Parent = ywelhopen
