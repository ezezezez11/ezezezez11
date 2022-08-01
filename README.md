local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("you noob hub", "BloodTheme")

local Tab = Window:NewTab("Menu")
local Section = Tab:NewSection("TELEPORT")

Section:NewButton("Vulcan", "go to Vulcan", function()
    local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(5, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(-608.023987, 952.999878, 155.225677, 0.691060841, -5.67977345e-08, -0.722796619, 7.41172101e-08, 1, -7.71756792e-09, 0.722796619, -4.82383591e-08, 0.691060841)}):Play()
end)

Section:NewButton("LXW", "go to LXW", function()
    local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(5, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(-14.7027941, 865.998352, -46.7465096, 0.999999762, -3.79899241e-08, 0.0007116411, 3.79933844e-08, 1, -4.84682294e-09, -0.0007116411, 4.87385909e-09, 0.999999762)}):Play()
end)

Section:NewButton("HEX Spitter", "go to HEX Spitter", function()
    local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(5, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(-583.526794, 1082.97864, 1086.36377, 0.606029153, 7.72299558e-08, 0.795442462, -5.46578782e-08, 1, -5.54479982e-08, -0.795442462, -9.87409443e-09, 0.606029153)}):Play()
end)

Section:NewButton("Red Missile Launcher", "go to Red Missile Launcher", function()
    local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(5, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(-353.553406, 1074.47144, 409.735138, 0.994664669, -2.95008231e-08, -0.103161067, 2.70223577e-08, 1, -2.54227572e-08, 0.103161067, 2.24994618e-08, 0.994664669)}):Play()
end)

local Tab = Window:NewTab("Farm")
local Section = Tab:NewSection("Auto Farm")

Section:NewToggle("Kill mon", "1+1", function(state)
    if state then
        print("Toggle On")
    else
        print("Toggle Off1")
    end
end)
