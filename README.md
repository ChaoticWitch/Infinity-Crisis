    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
    local Window = Library.CreateLib("Infinity Crisis GUi", "GrapeTheme")
    local Tab = Window:NewTab("Characters")
    local Section = Tab:NewSection("characters")
    Section:NewButton("Scarlet witch Gamepass", "", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "Scarlet Witch"

game:GetService("ReplicatedStorage").SelectChar:FireServer(ohString1)
        print("Clicked")
    end)
    Section:NewButton("Jean Grey Marvel Girl Gamepass", "", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "Jean Grey"

game:GetService("ReplicatedStorage").SelectChar:FireServer(ohString1)
        print("Clicked")
    end)
    Section:NewButton("Jinx", "", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "Jinx"

game:GetService("ReplicatedStorage").SelectChar:FireServer(ohString1)
        print("Clicked")
    end)
    Section:NewButton("Kory", "", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "Kory Anders"

game:GetService("ReplicatedStorage").SelectChar:FireServer(ohString1)
        print("Clicked")
    end)
    Section:NewButton("Wanda Aou", "", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "Wanda Maximoff (AOU)"

game:GetService("ReplicatedStorage").SelectChar:FireServer(ohString1)
        print("Clicked")
    end)
    local Tab = Window:NewTab("Powers")
    local Section = Tab:NewSection("Powers")
    Section:NewButton("Start Invisible", "", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "startinvis"
local ohVector32 = Vector3.new(-634.882568359375, 0.08594989776611328, 113.07838439941406)

game:GetService("ReplicatedStorage").Events.Abilities.InvisibleWoman:FireServer(ohString1, ohVector32)
        print("Clicked")
    end)
    Section:NewButton("End Invisible", "", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "invisend"
local ohVector32 = Vector3.new(-671.7885131835938, 0.08594989776611328, 178.43453979492188)

game:GetService("ReplicatedStorage").Events.Abilities.InvisibleWoman:FireServer(ohString1, ohVector32)
        print("Clicked")
    end)
    Section:NewButton("Time stop", "", function()
-- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "TimeStop"
local ohVector32 = Vector3.new(-335.0751953125, 120.44416809082031, 254.07220458984375)

game:GetService("ReplicatedStorage").Events.Abilities.ScarletWitch:FireServer(ohString1, ohVector32)
        print("Clicked")
    end)
    Section:NewButton("Jinx's Self Heal", "", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "SelfHeal"
local ohVector32 = Vector3.new(-677.8939819335938, 0.08594989776611328, 156.69871520996094)

game:GetService("ReplicatedStorage").Events.Abilities.Jinx:FireServer(ohString1, ohVector32)
        print("Clicked")
    end)
    Section:NewButton("Jinx's Earthquake", "", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "quake"
local ohVector32 = Vector3.new(-688.3760375976562, 0.08597494661808014, 89.26690673828125)

game:GetService("ReplicatedStorage").Events.Abilities.Jinx:FireServer(ohString1, ohVector32)
        print("Clicked")
    end)
    Section:NewButton("Scarlet Witch's Outburst Shockwave", "ButtonInfo", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "AOEMOVE"
local ohVector32 = Vector3.new(-1079.58203125, 36.50608444213867, -761.3397216796875)

game:GetService("ReplicatedStorage").Events.Abilities.ScarletWitch:FireServer(ohString1, ohVector32)
        print("Clicked")
    end)
    Section:NewButton("Kory's Stomp", "", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "Stomp"
local ohVector32 = Vector3.new(-744.0151977539062, -0.00000762939453125, 92.23899841308594)

game:GetService("ReplicatedStorage").Events.Abilities.KoryAnders:FireServer(ohString1, ohVector32)
        print("Clicked")
    end)
    Section:NewButton("Wanda Aou Wave", "Only og wanda aou can activate this", function()
        -- This script was generated by Hydroxide's RemoteSpy: https://github.com/Upbolt/Hydroxide

local ohString1 = "UltronDeathWave"
local ohVector32 = Vector3.new(-678.02734375, 0.08594989776611328, 148.04795837402344)

game:GetService("ReplicatedStorage").Events.Abilities.ScarletWitch:FireServer(ohString1, ohVector32)
        print("Clicked")
    end)
    local Tab = Window:NewTab("Credits&Others")
    local Section = Tab:NewSection("Made by Scarlet Witch")
    local Section = Tab:NewSection("discord: Scarlet Witch#9326")
    local Section = Tab:NewSection("Dont worry this script is not fully complete")
    Section:NewButton("Infinite Yeild", "", function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
        print("Clicked")
    end)
