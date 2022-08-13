
-- no necesita configuracion para las transformaciones ya esta todo configurado
whitelist = false
if game.Players.LocalPlayer.Name == 'X_Javi321'or 'orJaBoN_56' or 'B3B3W4P0' then
    whitelist = true
end
if whitelist == true then
if _G.BrolyEarth == false then
repeat wait()
 until game:IsLoaded()
   game.Players.LocalPlayer.PlayerGui:WaitForChild("HUD")
   wait(2)

game.Players.LocalPlayer.PlayerGui.HUD.FullSize.Money.Text = "Creado/Made By Joseluis#2689"
game.Players.LocalPlayer.PlayerGui.HUD.FullSize.Money.TextSize = 60

-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local TextLabel = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextLabel.Parent = ScreenGui
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.715630889, 0, 0.713450313, 0)
TextLabel.Size = UDim2.new(0, 393, 0, 180)
TextLabel.Text = "AutoBroly For all race Created By Joseluis#2689"
TextLabel.TextColor3 = Color3.fromRGB(17, 17, 255)
TextLabel.TextSize = 35.000
TextLabel.TextWrapped = true
if not game:IsLoaded() then
    local loadedcheck = Instance.new("Message",workspace)
    loadedcheck.Text = 'Loading...'
    game.Loaded:Wait(10)
    loadedcheck:Destroy()
end

function Twn(HRP, Place, Length)
    local Twn =
        game:GetService("TweenService"):Create(
        HRP,
        TweenInfo.new(Length, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut),
        {CFrame = Place}
    )
    Twn:Play()
    Twn.Completed:Wait()
end

       if game.PlaceId == 536102540 then
    game:GetService("TeleportService"):Teleport(3565304751)
end



if game.PlaceId == 3565304751 then 
    
 function Twn(HRP, Place, Length)
    local Twn =
        game:GetService("TweenService"):Create(
        HRP,
        TweenInfo.new(Length, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut),                                                                                     
        {CFrame = Place}
    )
    Twn:Play()
    Twn.Completed:Wait()
end
 local Live = game:WaitForChild("Workspace").Live
local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)
 
    wait(1)
   
    local Pads = {}
    for i, v in pairs(game:WaitForChild("Workspace"):GetChildren()) do
        if v.Name:find("BrolyTeleport") then
            table.insert(Pads, v)
        end
    end
    local pad = Pads[math.random(1, 7)]
    print(pad.Name)
    Twn(Char.HumanoidRootPart, pad.PrimaryPart.CFrame, 1)
    
    wait(50)
    game:GetService("TeleportService"):teleport(536102540)
end
if game.PlaceId == 2050207304 then
if _G.Antileech == true then
if game.Players.NumPlayers > 1 then
        game:GetService("TeleportService"):Teleport(3565304751)
    end end


wait(0.7)
if game.Players.LocalPlayer.Character.Race.Value == "Saiyan" or "Jiren" or "Namekian" or "Majin" or "Frieza" then
function getNil(name,class) for _,v in pairs(getnilinstances())do if v.ClassName==class and v.Name==name then return v;end end end

local args = {
    [1] = {
        [1] = "x"
    },
    [2] = CFrame.new(Vector3.new(-39.20831298828125, 235, -73.505615234375), Vector3.new(0.01250077597796917, -0.29617342352867126, -0.9550524353981018)),
    [3] = getNil("InputObject", "InputObject")
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack(args))

wait(4)
local args = {
    [1] = "h"
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Transform:FireServer(unpack(args))
wait(0.9)
function getNil(name,class) for _,v in pairs(getnilinstances())do if v.ClassName==class and v.Name==name then return v;end end end

local args = {
    [1] = {
        [1] = "xoff"
    },
    [2] = CFrame.new(Vector3.new(-6435.54345703125, 1055.144287109375, 7579.7900390625), Vector3.new(-0.6407649517059326, 0.08111581206321716, 0.7634400129318237)),
    [3] = getNil("InputObject", "InputObject")
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack(args))
else
    local args = {
    [1] = "g"
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Transform:FireServer(unpack(args))
end
     wait(0.4)       
local Live = game:WaitForChild("Workspace").Live
local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)
local plr = game.Players.LocalPlayer


local tpbroly = game:GetService("RunService").RenderStepped:connect(function()
    
    local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game.Workspace.Live["Broly BR"].HumanoidRootPart.Position) + Vector3.new(0, 0, 4)
        game.Workspace.CurrentCamera.CFrame =
                CFrame.new(Char.HumanoidRootPart.Position, B.HumanoidRootPart.Position)
    end)



game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Dragon Crush"])
game.Players.LocalPlayer.Character["Dragon Crush"]:Activate() 
game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["Flip"]:Destroy()
			 wait(0.5)

local SP = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.SP
local Plr = game.Players.LocalPlayer
local Run = game:GetService("RunService")
local BrolyHum = game.Workspace.Live["Broly BR"].Humanoid
local Hum = Plr.Character.Humanoid

game.Workspace:WaitForChild("Live")
game.Workspace.Live:WaitForChild(Plr.Name)
Run.Stepped:connect(function()
SP.Visible = true
SP.BackgroundColor3 = Color3.fromRGB(0,0,0)
SP.Text = "Broly's Health: "..math.floor(BrolyHum.Health/BrolyHum.MaxHealth*100).."%"..
" ┃ ".."Run Time : " ..math.floor(Workspace.DistributedGameTime).."/"
end)
 
game:GetService("RunService").RenderStepped:connect(function()

    			local args = {
    [1] = true
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.EatSenzu:FireServer(unpack(args))

	   Player = game.Players.LocalPlayer.Character
                for i,v in pairs(Player:GetChildren()) do
                if v.Name == "Justice Combination" then
                x = Player:WaitForChild("Action")
                if x then wait() x:Destroy() end end
                if v.Name == "Action" then v:Destroy() end
                if v.Name == "Attacking" then v:Destroy() end
                if v.Name == "Using" then v:Destroy() end
                if v.Name == "hyper" then v:Destroy() end
                if v.Name == "Hyper" then v:Destroy() end
                if v.Name == "heavy" then v:Destroy() end
                if v.Name == "KiBlasted" then v:Destroy() end
                if v.Name == "Tele" then v:Destroy() end
                if v.Name == "tele" then v:Destroy() end
                if v.Name == "Killed" then v:Destroy() end
                if v.Name == "Slow" then v:Destroy() end
                if v.Name == "MoveStart" then v:Destroy() end
                if v.Name == "Look" then v:Destroy() end
                if v.Name == "Activity" then v:Destroy() end
                if v.Name == "Block" and v.Value == true then v.Value = false 
if game.Players.LocalPlayer.Character.Head:FindFirstChild("KnockBacked") then
            game.Players.LocalPlayer.Character.Head.KnockBacked:Destroy()
            end
            if game.Players.LocalPlayer.Character.Head:FindFirstChild("NotHardBack") then
            game.Players.LocalPlayer.Character.Head.NotHardBack:Destroy()
            end
            local SP = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.SP
local Plr = game.Players.LocalPlayer
local BrolyHum = game.Workspace.Live["Broly BR"].Humanoid


game.Workspace:WaitForChild("Live")
game.Workspace.Live:WaitForChild(Plr.Name)
SP.Visible = true
SP.BackgroundColor3 = Color3.fromRGB(0,0,0)
SP.Text = "Broly's Health: "..math.floor(BrolyHum.Health/BrolyHum.MaxHealth*100).."%"..
" ┃ ".."Run Time : " ..math.floor(Workspace.DistributedGameTime).."/"


   local B = Live:WaitForChild("Broly BR")


for i,v in pairs(game.Workspace:GetChildren()) do
game.Workspace.Live["Broly BR"].HumanoidRootPart:GetChildren()
if v.Name == 'ExplosiveWave' then
v:Destroy()
end end
local Live = game:WaitForChild("Workspace").Live
local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)
if Char.Humanoid.Health < 0 then
                game:GetService("TeleportService"):Teleport(3565304751)
            end


local Live = game:WaitForChild("Workspace").Live
local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)
if Char.Humanoid.Health < 31 then
                local args = {
    [1] = "h"
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Transform:FireServer(unpack(args))

            end
        local Char =  game.Players.LocalPlayer.Character
if Char.Humanoid.Health < 1.5 then
                game:GetService("TeleportService"):Teleport(3565304751)
            end
	   end end 

      if Char.Humanoid.Health < 1.5 then
                game:GetService("TeleportService"):Teleport(3565304751)
                
      end
      if game.Players.LocalPlayer.Character.Ki.Value < 32 then
              function getNil(name,class) for _,v in pairs(getnilinstances())do if v.ClassName==class and v.Name==name then return v;end end end

local args = {
    [1] = {
        [1] = "m2"
    },
    [2] = CFrame.new(Vector3.new(-35.57574462890625, 235, -66.59344482421875), Vector3.new(0.1108170747756958, -0.33328282833099365, -0.9362917542457581)),
    [3] = getNil("InputObject", "InputObject"),
    [4] = false
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack(args))

                


end
	   end)
    
       wait()
       
			 
			 		repeat
			 		 wait()
       game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move1])
game.Players.LocalPlayer.Character[Move1]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move2])
game.Players.LocalPlayer.Character[Move2]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move3])
game.Players.LocalPlayer.Character[Move3]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move4])
game.Players.LocalPlayer.Character[Move4]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move5])
game.Players.LocalPlayer.Character[Move5]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move6])
game.Players.LocalPlayer.Character[Move6]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move7])
game.Players.LocalPlayer.Character[Move7]:Activate() 
		
        local B = Live:WaitForChild("Broly BR")


		until B.Humanoid.Health < .1

wait(3)
    game:GetService("TeleportService"):Teleport(3565304751)
		 wait(1)


end end
if _G.BrolyEarth == true then
    repeat wait()
 until game:IsLoaded()
   game.Players.LocalPlayer.PlayerGui:WaitForChild("HUD")
   wait(2)

game.Players.LocalPlayer.PlayerGui.HUD.FullSize.Money.Text = "Creado/Made By Joseluis#2689"
game.Players.LocalPlayer.PlayerGui.HUD.FullSize.Money.TextSize = 60

-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local TextLabel = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextLabel.Parent = ScreenGui
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.715630889, 0, 0.713450313, 0)
TextLabel.Size = UDim2.new(0, 393, 0, 180)
TextLabel.Text = "AutoBroly Androids Created By Joseluis#2689"
TextLabel.TextColor3 = Color3.fromRGB(17, 17, 255)
TextLabel.TextSize = 35.000
TextLabel.TextWrapped = true
if not game:IsLoaded() then
    local loadedcheck = Instance.new("Message",workspace)
    loadedcheck.Text = 'Loading...'
    game.Loaded:Wait(10)
    loadedcheck:Destroy()
end
       if game.PlaceId == 3565304751 then
    game:GetService("TeleportService"):Teleport(536102540)
end

function Twn(HRP, Place, Length)
    local Twn =
        game:GetService("TweenService"):Create(
        HRP,
        TweenInfo.new(Length, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut),
        {CFrame = Place}
    )
    Twn:Play()
    Twn.Completed:Wait()
end

       if game.PlaceId == 536102540 then
           while wait() do
     function Twn(HRP, Place, Length)
    local Twn =
        game:GetService("TweenService"):Create(
        HRP,
        TweenInfo.new(Length, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut),
        {CFrame = Place}
    )
    Twn:Play()
    Twn.Completed:Wait()
end
 local Live = game:WaitForChild("Workspace").Live
local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)
 Twn(Char:WaitForChild("HumanoidRootPart"), CFrame.new(2752, 3945, -2270), 1)
end
end



if game.PlaceId == 2050207304 then
if _G.Antileech == true then
if game.Players.NumPlayers > 1 then
        game:GetService("TeleportService"):Teleport(536102540)
    end end


wait(0.7)

if game.Players.LocalPlayer.Character.Race.Value == "Saiyan" or "Jiren" or "Namekian" or "Majin" or "Frieza" then
function getNil(name,class) for _,v in pairs(getnilinstances())do if v.ClassName==class and v.Name==name then return v;end end end

local args = {
    [1] = {
        [1] = "x"
    },
    [2] = CFrame.new(Vector3.new(-39.20831298828125, 235, -73.505615234375), Vector3.new(0.01250077597796917, -0.29617342352867126, -0.9550524353981018)),
    [3] = getNil("InputObject", "InputObject")
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack(args))

wait(4)
local args = {
    [1] = "h"
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Transform:FireServer(unpack(args))
wait(0.9)
function getNil(name,class) for _,v in pairs(getnilinstances())do if v.ClassName==class and v.Name==name then return v;end end end

local args = {
    [1] = {
        [1] = "xoff"
    },
    [2] = CFrame.new(Vector3.new(-6435.54345703125, 1055.144287109375, 7579.7900390625), Vector3.new(-0.6407649517059326, 0.08111581206321716, 0.7634400129318237)),
    [3] = getNil("InputObject", "InputObject")
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack(args))
else
    local args = {
    [1] = "g"
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Transform:FireServer(unpack(args))
end

     wait(0.4)       
local Live = game:WaitForChild("Workspace").Live
local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)
local plr = game.Players.LocalPlayer
wait(0.2)
local tpbroly = game:GetService("RunService").RenderStepped:connect(function()
    
    local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game.Workspace.Live["Broly BR"].HumanoidRootPart.Position) + Vector3.new(0, 0, 4)
        game.Workspace.CurrentCamera.CFrame =
                CFrame.new(Char.HumanoidRootPart.Position, B.HumanoidRootPart.Position)
                game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
    end)



game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Dragon Crush"])
game.Players.LocalPlayer.Character["Dragon Crush"]:Activate() 
game.Workspace.Live[plr.Name]["Dragon Crush"].Activator["Flip"]:Destroy()

			 
wait(0.5)

local SP = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.SP
local Plr = game.Players.LocalPlayer
local Run = game:GetService("RunService")
local BrolyHum = game.Workspace.Live["Broly BR"].Humanoid
local Hum = Plr.Character.Humanoid

game.Workspace:WaitForChild("Live")
game.Workspace.Live:WaitForChild(Plr.Name)
Run.Stepped:connect(function()
SP.Visible = true
SP.BackgroundColor3 = Color3.fromRGB(0,0,0)
SP.Text = "Broly's Health: "..math.floor(BrolyHum.Health/BrolyHum.MaxHealth*100).."%"..
" ┃ ".."Run Time : " ..math.floor(Workspace.DistributedGameTime).."/"
end)
 
game:GetService("RunService").RenderStepped:connect(function()

    			local args = {
    [1] = true
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.EatSenzu:FireServer(unpack(args))

	   Player = game.Players.LocalPlayer.Character
                for i,v in pairs(Player:GetChildren()) do
                if v.Name == "Justice Combination" then
                x = Player:WaitForChild("Action")
                if x then wait() x:Destroy() end end
                if v.Name == "Action" then v:Destroy() end
                if v.Name == "Attacking" then v:Destroy() end
                if v.Name == "Using" then v:Destroy() end
                if v.Name == "hyper" then v:Destroy() end
                if v.Name == "Hyper" then v:Destroy() end
                if v.Name == "heavy" then v:Destroy() end
                if v.Name == "KiBlasted" then v:Destroy() end
                if v.Name == "Tele" then v:Destroy() end
                if v.Name == "tele" then v:Destroy() end
                if v.Name == "Killed" then v:Destroy() end
                if v.Name == "Slow" then v:Destroy() end
                if v.Name == "MoveStart" then v:Destroy() end
                if v.Name == "Look" then v:Destroy() end
                if v.Name == "Activity" then v:Destroy() end
                if v.Name == "Block" and v.Value == true then v.Value = false 
if game.Players.LocalPlayer.Character.Head:FindFirstChild("KnockBacked") then
            game.Players.LocalPlayer.Character.Head.KnockBacked:Destroy()
            end
            if game.Players.LocalPlayer.Character.Head:FindFirstChild("NotHardBack") then
            game.Players.LocalPlayer.Character.Head.NotHardBack:Destroy()
            end
            local SP = game:GetService("Players").LocalPlayer.PlayerGui.HUD.Bottom.SP
local Plr = game.Players.LocalPlayer
local BrolyHum = game.Workspace.Live["Broly BR"].Humanoid


game.Workspace:WaitForChild("Live")
game.Workspace.Live:WaitForChild(Plr.Name)
SP.Visible = true
SP.BackgroundColor3 = Color3.fromRGB(0,0,0)
SP.Text = "Broly's Health: "..math.floor(BrolyHum.Health/BrolyHum.MaxHealth*100).."%"..
" ┃ ".."Run Time : " ..math.floor(Workspace.DistributedGameTime).."/"


   local B = Live:WaitForChild("Broly BR")


for i,v in pairs(game.Workspace:GetChildren()) do
game.Workspace.Live["Broly BR"].HumanoidRootPart:GetChildren()
if v.Name == 'ExplosiveWave' then
v:Destroy()
end end
local Live = game:WaitForChild("Workspace").Live
local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)
if Char.Humanoid.Health < 0 then
                game:GetService("TeleportService"):Teleport(536102540)
            end


local Live = game:WaitForChild("Workspace").Live
local Char = Live:WaitForChild(game.Players.LocalPlayer.Name)
if Char.Humanoid.Health < 31 then
                local args = {
    [1] = "h"
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Transform:FireServer(unpack(args))

            end
        local Char =  game.Players.LocalPlayer.Character
if Char.Humanoid.Health < 1.5 then
                game:GetService("TeleportService"):Teleport(536102540)
            end
	   end end 

      if Char.Humanoid.Health < 1.5 then
                game:GetService("TeleportService"):Teleport(536102540)
                
      end
      if game.Players.LocalPlayer.Character.Ki.Value < 32 then
              function getNil(name,class) for _,v in pairs(getnilinstances())do if v.ClassName==class and v.Name==name then return v;end end end

local args = {
    [1] = {
        [1] = "m2"
    },
    [2] = CFrame.new(Vector3.new(-35.57574462890625, 235, -66.59344482421875), Vector3.new(0.1108170747756958, -0.33328282833099365, -0.9362917542457581)),
    [3] = getNil("InputObject", "InputObject"),
    [4] = false
}

game:GetService("Players").LocalPlayer.Backpack.ServerTraits.Input:FireServer(unpack(args))

                


end
	   end)
    
       wait()
       
			 
			 		repeat
			 		 
       game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move1])
game.Players.LocalPlayer.Character[Move1]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move2])
game.Players.LocalPlayer.Character[Move2]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move3])
game.Players.LocalPlayer.Character[Move3]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move4])
game.Players.LocalPlayer.Character[Move4]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move5])
game.Players.LocalPlayer.Character[Move5]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move6])
game.Players.LocalPlayer.Character[Move6]:Activate() 
wait()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack[Move7])
game.Players.LocalPlayer.Character[Move7]:Activate() 
		wait()
        local B = Live:WaitForChild("Broly BR")


		until B.Humanoid.Health < .1

wait(3)
    game:GetService("TeleportService"):Teleport(536102540)
		 wait(1)
    
end
end
end
if whitelist == false then
    game.Players.LocalPlayer:Kick() end
