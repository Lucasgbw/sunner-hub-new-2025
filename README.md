debugX = true

local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "sunner hub👻",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "script para brookhaven rp",
   LoadingSubtitle = "criado por NYYX7",
   Theme = "Default", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

 local args = {
    [1] = "RolePlayName",
    [2] = "sunner user👻"
}

game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1RPNam1eTex1t"):FireServer(unpack(args))

-- ID do som a ser reproduzido quando o código for executado
local soundId = "rbxassetid://103211341252816"

-- Função para tocar o som
local function playSound()
    local sound = Instance.new("Sound")
    sound.SoundId = soundId
    sound.Parent = game.Workspace -- Coloque no Workspace para garantir que seja ouvido
    sound:Play()
end

-- Tocar o som assim que o script for executado
playSound()

Rayfield:Notify({
   Title = "sejam bem vindos ao Sunner hub👻",
   Content = "Welcome to the sunner hub👻",
   Duration = 6.5,
   Image = 79564224967811,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "belexa",
         Callback = function()
         print("The user tapped Okay!")
      end
   },
},
})

local Tab = Window:CreateTab("scripts v1🎶", 103006981698580) -- Title, Image

local Section = Tab:CreateSection("Veja os melhores scritps para você!!🥶")

local Button = Tab:CreateButton({
   Name = "FLY GUI",
   Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/YSL3xKYU'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Nameless Admin(muito op)",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Nameless-Admin-V2-24856"))()
   -- The function that takes place when the button is pressed
   end,
})


local Button = Tab:CreateButton({
   Name = "script de reverso",
   Callback = function()loadstring(game:HttpGet("https://mscripts.vercel.app/scfiles/reverse-script.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script de animação r15 para r6|animation r6",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Imagnir/r6_anims_for_r15/main/r6_anims.lua", true))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "chat bypasser op",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-AK-CHAT-BYPASSER-26254"))()
   -- The function that takes place when the button is pressed
   end,
})


local Button = Tab:CreateButton({
   Name = "the darkones",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/TheDarkoneMarcillisePex/Other-Scripts/main/Brook%20Haven%20Gui'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "blackhole op",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/GoofyBlox/GoofyZ/refs/heads/main/Best/Vortex.lua", true))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "infinite yield🤖",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "fake lag🏺",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-FAKE-LAG-22520"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "redz hub para blox fruits",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/realredz/BloxFruits/refs/heads/main/Source.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "chat bypass ",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-FilterEvader-v1-Chat-Bypass-26225"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "chat bypasser",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Chat-bypass-v2-chatglyph-26394"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "chat bypassee",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Gaze-bypass-REIMAGINED-26354"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Fe orbitar o player",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-FE-Orbit-14486"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "copiar avatar/ VISUAL!!!!",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/refs/heads/main/Copy%20Avatar'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script de salvar o servidor que você estava antes.",
   Callback = function() loadstring(game:HttpGet('https://pastefy.app/S7xNJSXX/raw'))()execute("Script17")
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "cannon FE",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Cannon%20Ball'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "serpente x",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/err0r129/SerpenteXbetaByDefense129/main/Serpente.Scripts"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "rochips painel🔑",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Rochips-Universal-21865"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "fe animação",
   Callback = function()loadstring(game:HttpGet('https://pastefy.app/S7xNJSXX/raw'))()execute("Script9")
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script freecam",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Freecam'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script vfly",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Flat-Kurdish-Vfly-13538"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Script de matemática (ou jogo da velha)",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/refs/heads/main/Math%20Problem'))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "ghost hub",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-GhostHub-16534"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "hitbox op",
   Callback = function()-- Gui to Lua
-- Version: 3.2

-- Instances:

local Close = Instance.new("TextButton")
local Open2 = Instance.new("ScreenGui")
local Open = Instance.new("TextButton")
local FightingGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local Cre = Instance.new("TextLabel")
local HitBox = Instance.new("TextBox")
local Red = Instance.new("TextBox")
local Green = Instance.new("TextBox")
local Blue = Instance.new("TextBox")
local TextLabel = Instance.new("TextLabel")

--Properties:

FightingGui.Name = "FightingGui"
FightingGui.Parent = game.CoreGui
FightingGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling


Open2.Name = "Tools"
Open2.Parent = game.CoreGui
Open2.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Open.Name = "Open"
Open.Parent = Open2
Open.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Open.Position = UDim2.new(0, 0, 0.451871663, 0)
Open.Size = UDim2.new(0, 78, 0, 50)
Open.Font = Enum.Font.SourceSans
Open.Text = "Open"
Open.TextColor3 = Color3.fromRGB(250, 0, 0)
Open.TextScaled = true
Open.TextSize = 14.000
Open.TextWrapped = true
Open.MouseButton1Down:Connect(function()
 FightingGui.Enabled = true
end)

Close.Name = "Close"
Close.Parent = main
Close.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Close.Position = UDim2.new(1, 0, -0.226244345, 0)
Close.Size = UDim2.new(0, 60, 0, 50)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true
Close.MouseButton1Down:Connect(function()
 FightingGui.Enabled = false
end)

main.Parent = FightingGui
main.Active = true
main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
main.Position = UDim2.new(0.073011741, 0, 0.237333342, 0)
main.Size = UDim2.new(0, 273, 0, 221)
main.Draggable = true

Cre.Name = "Cre"
Cre.Parent = main
Cre.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Cre.Position = UDim2.new(0, 0, -0.226244345, 0)
Cre.Size = UDim2.new(0, 273, 0, 50)
Cre.Font = Enum.Font.SourceSans
Cre.Text = "Script made by seu pai☄️"
Cre.TextColor3 = Color3.fromRGB(0, 0, 0)
Cre.TextScaled = true
Cre.TextSize = 14.000
Cre.TextWrapped = true

HitBox.Name = "HitBox frost"
HitBox.Parent = main
HitBox.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
HitBox.Position = UDim2.new(0.0586080588, 0, 0.0995475128, 0)
HitBox.Size = UDim2.new(0, 65, 0, 50)
HitBox.Font = Enum.Font.SourceSans
HitBox.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
HitBox.PlaceholderText = "Hitbox"
HitBox.Text = ""
HitBox.TextColor3 = Color3.fromRGB(0, 0, 0)
HitBox.TextScaled = true
HitBox.TextSize = 14.000
HitBox.TextWrapped = true

Red.Name = "Red"
Red.Parent = main
Red.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Red.Position = UDim2.new(0.485832304, 0, 0.0995475128, 0)
Red.Size = UDim2.new(0, 37, 0, 31)
Red.Font = Enum.Font.SourceSans
Red.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Red.PlaceholderText = "Red"
Red.Text = ""
Red.TextColor3 = Color3.fromRGB(0, 0, 0)
Red.TextSize = 14.000

Green.Name = "Green"
Green.Parent = main
Green.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
Green.Position = UDim2.new(0.665319502, 0, 0.0995475128, 0)
Green.Size = UDim2.new(0, 37, 0, 31)
Green.Font = Enum.Font.SourceSans
Green.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Green.PlaceholderText = "Green"
Green.Text = ""
Green.TextColor3 = Color3.fromRGB(0, 0, 0)
Green.TextSize = 14.000

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.Position = UDim2.new(0.47118023, 0, 0.325791866, 0)
TextLabel.Size = UDim2.new(0, 140, 0, 37)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Colors"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

Blue.Name = "Blue"
Blue.Parent = main
Blue.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
Blue.Position = UDim2.new(0.837480664, 0, 0.0995475128, 0)
Blue.Size = UDim2.new(0, 37, 0, 31)
Blue.Font = Enum.Font.SourceSans
Blue.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Blue.PlaceholderText = "Blue"
Blue.Text = ""
Blue.TextColor3 = Color3.fromRGB(0, 0, 0)
Blue.TextSize = 14.000
game:GetService('RunService').RenderStepped:connect(function()
 for i,v in next, game:GetService('Players'):GetPlayers() do
  if v.Name ~= game:GetService('Players').LocalPlayer.Name then
   v.Character.HumanoidRootPart.Size = Vector3.new(HitBox.Text,HitBox.Text,HitBox.Text)
   v.Character.HumanoidRootPart.Transparency = 0.8
   v.Character.HumanoidRootPart.Color = Color3.new(Red.Text,Green.Text,Blue.Text)
   v.Character.HumanoidRootPart.Material = "Neon"
   v.Character.HumanoidRootPart.CanCollide = false
  end
 end
end)
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "sander x💀⛎",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/NormalSS.lua'))()
   -- The function that takes place when the button is pressed
   end,
})

local Section = Tab:CreateSection("a key do yhub e esta daqui👉YFDQMASrE")

local Button = Tab:CreateButton({
   Name = "YHUB(somente para brookhaven rp.)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Luarmor123/community-Y-HUB/refs/heads/main/YHUB%20ENGLISH"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "tiger x📿",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-tiger-x-hub-21766"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "tela esticada",
   Callback = function()getgenv().Resolution = {
    [".gg/scripters"] = 0.69
}

local Camera = workspace.CurrentCamera
if getgenv().gg_scripters == nil then
    game:GetService("RunService").RenderStepped:Connect(
        function()
            Camera.CFrame = Camera.CFrame * CFrame.new(0, 0, 0, 1, 0, 0, 0, getgenv().Resolution[".gg/scripters"], 0, 0, 0, 1)
        end
    )
end
getgenv().gg_scripters = "Aori0001"
       -- The function that takes place when the button is pressed
   end,
})

local Tab = Window:CreateTab("SCRIPTS V2📟", 103006981698580) -- Title, Image

local Button = Tab:CreateButton({
   Name = "super rings v6",
   Callback = function()-- The tags get stealed and i will not leak it
local Players = game:GetService("Players")
local RunService = game:GetService("RunService")
local UserInputService = game:GetService("UserInputService")
local SoundService = game:GetService("SoundService")
local StarterGui = game:GetService("StarterGui")
local HttpService = game:GetService("HttpService")

local LocalPlayer = Players.LocalPlayer

-- Sound Effects
local function playSound(soundId)
    local sound = Instance.new("Sound")
    sound.SoundId = "rbxassetid://" .. soundId
    sound.Parent = SoundService
    sound:Play()
    sound.Ended:Connect(function()
        sound:Destroy()
    end)
end

-- Play initial sound
playSound("2865227271")

-- GUI Creation
local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "SuperRingPartsGUI"
ScreenGui.ResetOnSpawn = false
ScreenGui.Parent = LocalPlayer:WaitForChild("PlayerGui")

local MainFrame = Instance.new("Frame")
MainFrame.Size = UDim2.new(0, 300, 0, 500)
MainFrame.Position = UDim2.new(0.5, -150, 0.5, -250)
MainFrame.BorderSizePixel = 0
MainFrame.Parent = ScreenGui

-- Make the GUI round
local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 20)
UICorner.Parent = MainFrame

local Title = Instance.new("TextLabel")
Title.Size = UDim2.new(1, 0, 0, 40)
Title.Position = UDim2.new(0, 0, 0, 0)
Title.Text = "Super Ring Parts V6 by lukas"
Title.TextColor3 = Color3.fromRGB(0, 0, 0)
Title.BackgroundColor3 = Color3.fromRGB(0, 204, 204)
Title.Font = Enum.Font.Fondamento
Title.TextSize = 22
Title.Parent = MainFrame

-- Round the title
local TitleCorner = Instance.new("UICorner")
TitleCorner.CornerRadius = UDim.new(0, 20)
TitleCorner.Parent = Title

local ToggleButton = Instance.new("TextButton")
ToggleButton.Size = UDim2.new(0.8, 0, 0, 40)
ToggleButton.Position = UDim2.new(0.1, 0, 0.1, 0)
ToggleButton.Text = "Ring Off"
ToggleButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
ToggleButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ToggleButton.Font = Enum.Font.Fondamento
ToggleButton.TextSize = 18
ToggleButton.Parent = MainFrame

-- Round the toggle button
local ToggleCorner = Instance.new("UICorner")
ToggleCorner.CornerRadius = UDim.new(0, 10)
ToggleCorner.Parent = ToggleButton

-- Configuration table
local config = {
    radius = 50,
    height = 100,
    rotationSpeed = 10,
    attractionStrength = 1000,
}

-- Save and load functions
local function saveConfig()
    local configStr = HttpService:JSONEncode(config)
    writefile("SuperRingPartsConfig.txt", configStr)
end

local function loadConfig()
    if isfile("SuperRingPartsConfig.txt") then
        local configStr = readfile("SuperRingPartsConfig.txt")
        config = HttpService:JSONDecode(configStr)
    end
end

loadConfig()

-- Function to create control buttons and textboxes
local function createControl(name, positionY, color, labelText, defaultValue, callback)
    local DecreaseButton = Instance.new("TextButton")
    DecreaseButton.Size = UDim2.new(0.2, 0, 0, 40)
    DecreaseButton.Position = UDim2.new(0.1, 0, positionY, 0)
    DecreaseButton.Text = "-"
    DecreaseButton.BackgroundColor3 = color
    DecreaseButton.TextColor3 = Color3.fromRGB(0, 0, 0)
    DecreaseButton.Font = Enum.Font.Fondamento
    DecreaseButton.TextSize = 18
    DecreaseButton.Parent = MainFrame

    local IncreaseButton = Instance.new("TextButton")
    IncreaseButton.Size = UDim2.new(0.2, 0, 0, 40)
    IncreaseButton.Position = UDim2.new(0.7, 0, positionY, 0)
    IncreaseButton.Text = "+"
    IncreaseButton.BackgroundColor3 = color
    IncreaseButton.TextColor3 = Color3.fromRGB(0, 0, 0)
    IncreaseButton.Font = Enum.Font.Fondamento
    IncreaseButton.TextSize = 18
    IncreaseButton.Parent = MainFrame

    local Display = Instance.new("TextLabel")
    Display.Size = UDim2.new(0.4, 0, 0, 40)
    Display.Position = UDim2.new(0.3, 0, positionY, 0)
    Display.Text = labelText .. ": " .. defaultValue
    Display.BackgroundColor3 = Color3.fromRGB(255, 153, 51)
    Display.TextColor3 = Color3.fromRGB(0, 0, 0)
    Display.Font = Enum.Font.Fondamento
    Display.TextSize = 18
    Display.Parent = MainFrame

    -- Add TextBox for input
    local TextBox = Instance.new("TextBox")
    TextBox.Size = UDim2.new(0.8, 0, 0, 35)
    TextBox.Position = UDim2.new(0.1, 0, positionY + 0.1, 0)
    TextBox.PlaceholderText = "Enter " .. labelText
    TextBox.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
    TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
    TextBox.Font = Enum.Font.Fondamento
    TextBox.TextSize = 18
    TextBox.Parent = MainFrame

    local TextBoxCorner = Instance.new("UICorner")
    TextBoxCorner.CornerRadius = UDim.new(0, 10)
    TextBoxCorner.Parent = TextBox

    DecreaseButton.MouseButton1Click:Connect(function()
        local value = tonumber(Display.Text:match("%d+"))
        value = math.max(0, value - 10)
        Display.Text = labelText .. ": " .. value
        callback(value)
        playSound("12221967")
        saveConfig()
    end)

    IncreaseButton.MouseButton1Click:Connect(function()
        local value = tonumber(Display.Text:match("%d+"))
        value = math.min(10000, value + 10)
        Display.Text = labelText .. ": " .. value
        callback(value)
        playSound("12221967")
        saveConfig()
    end)

    TextBox.FocusLost:Connect(function(enterPressed)
        if enterPressed then
            local newValue = tonumber(TextBox.Text)
            if newValue then
                newValue = math.clamp(newValue, 0, 10000)
                Display.Text = labelText .. ": " .. newValue
                TextBox.Text = ""
                callback(newValue)
                playSound("12221967")
                saveConfig()
            else
                TextBox.Text = ""
            end
        end
    end)
end

createControl("Radius", 0.2, Color3.fromRGB(153, 153, 0), "Radius", config.radius, function(value)
    config.radius = value
    saveConfig()
end)

createControl("Height", 0.4, Color3.fromRGB(153, 0, 153), "Height", config.height, function(value)
    config.height = value
    saveConfig()
end)

createControl("RotationSpeed", 0.6, Color3.fromRGB(0, 153, 153), "Rotation Speed", config.rotationSpeed, function(value)
    config.rotationSpeed = value
    saveConfig()
end)

createControl("AttractionStrength", 0.8, Color3.fromRGB(153, 0, 0), "Attraction Strength", config.attractionStrength, function(value)
    config.attractionStrength = value
    saveConfig()
end)

-- Add minimize button
local MinimizeButton = Instance.new("TextButton")
MinimizeButton.Size = UDim2.new(0, 30, 0, 30)
MinimizeButton.Position = UDim2.new(1, -35, 0, 5)
MinimizeButton.Text = "-"
MinimizeButton.BackgroundColor3 = Color3.fromRGB(255, 255, 0)
MinimizeButton.TextColor3 = Color3.fromRGB(0, 0, 0)
MinimizeButton.Font = Enum.Font.Fondamento
MinimizeButton.TextSize = 15
MinimizeButton.Parent = MainFrame

-- Round the minimize button
local MinimizeCorner = Instance.new("UICorner")
MinimizeCorner.CornerRadius = UDim.new(0, 15)
MinimizeCorner.Parent = MinimizeButton

-- Minimize functionality
local minimized = false
MinimizeButton.MouseButton1Click:Connect(function()
    minimized = not minimized
    if minimized then
        MainFrame:TweenSize(UDim2.new(0, 300, 0, 40), "Out", "Quad", 0.3, true)
        MinimizeButton.Text = "+"
        for _, child in pairs(MainFrame:GetChildren()) do
            if child:IsA("GuiObject") and child ~= Title and child ~= MinimizeButton then
                child.Visible = false
            end
        end
    else
        MainFrame:TweenSize(UDim2.new(0, 300, 0, 500), "Out", "Quad", 0.3, true)
        MinimizeButton.Text = "-"
        for _, child in pairs(MainFrame:GetChildren()) do
            if child:IsA("GuiObject") then
                child.Visible = true
            end
        end
    end
    playSound("12221967")
end)

-- Make GUI draggable
local dragging
local dragInput
local dragStart
local startPos

local function update(input)
    local delta = input.Position - dragStart
    MainFrame.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
end

MainFrame.InputBegan:Connect(function(input)
    if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
        dragging = true
        dragStart = input.Position
        startPos = MainFrame.Position
        
        input.Changed:Connect(function()
            if input.UserInputState == Enum.UserInputState.End then
                dragging = false
            end
        end)
    end
end)

MainFrame.InputChanged:Connect(function(input)
    if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
        dragInput = input
    end
end)

UserInputService.InputChanged:Connect(function(input)
    if input == dragInput and dragging then
        update(input)
    end
end)

-- Ring Parts Claim
local Workspace = game:GetService("Workspace")

local character = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

local Folder = Instance.new("Folder", Workspace)
local Part = Instance.new("Part", Folder)
local Attachment1 = Instance.new("Attachment", Part)
Part.Anchored = true
Part.CanCollide = false
Part.Transparency = 1

if not getgenv().Network then
    getgenv().Network = {
        BaseParts = {},
        Velocity = Vector3.new(14.46262424, 14.46262424, 14.46262424)
    }

    Network.RetainPart = function(Part)
        if typeof(Part) == "Instance" and Part:IsA("BasePart") and Part:IsDescendantOf(Workspace) then
            table.insert(Network.BaseParts, Part)
            Part.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
            Part.CanCollide = false
        end
    end

    local function EnablePartControl()
        LocalPlayer.ReplicationFocus = Workspace
        RunService.Heartbeat:Connect(function()
            sethiddenproperty(LocalPlayer, "SimulationRadius", math.huge)
            for _, Part in pairs(Network.BaseParts) do
                if Part:IsDescendantOf(Workspace) then
                    Part.Velocity = Network.Velocity
                end
            end
        end)
    end

    EnablePartControl()
end

local function ForcePart(v)
    if v:IsA("Part") and not v.Anchored and not v.Parent:FindFirstChild("Humanoid") and not v.Parent:FindFirstChild("Head") and v.Name ~= "Handle" then
        for _, x in next, v:GetChildren() do
            if x:IsA("BodyAngularVelocity") or x:IsA("BodyForce") or x:IsA("BodyGyro") or x:IsA("BodyPosition") or x:IsA("BodyThrust") or x:IsA("BodyVelocity") or x:IsA("RocketPropulsion") then
                x:Destroy()
            end
        end
        if v:FindFirstChild("Attachment") then
            v:FindFirstChild("Attachment"):Destroy()
        end
        if v:FindFirstChild("AlignPosition") then
            v:FindFirstChild("AlignPosition"):Destroy()
        end
        if v:FindFirstChild("Torque") then
            v:FindFirstChild("Torque"):Destroy()
        end
        v.CanCollide = false
        local Torque = Instance.new("Torque", v)
        Torque.Torque = Vector3.new(100000, 100000, 100000)
        local AlignPosition = Instance.new("AlignPosition", v)
        local Attachment2 = Instance.new("Attachment", v)
        Torque.Attachment0 = Attachment2
        AlignPosition.MaxForce = 9999999999999999999999999999999
        AlignPosition.MaxVelocity = math.huge
        AlignPosition.Responsiveness = 200
        AlignPosition.Attachment0 = Attachment2
        AlignPosition.Attachment1 = Attachment1
    end
end

-- Edits
local ringPartsEnabled = false

local function RetainPart(Part)
    if Part:IsA("BasePart") and not Part.Anchored and Part:IsDescendantOf(workspace) then
        if Part.Parent == LocalPlayer.Character or Part:IsDescendantOf(LocalPlayer.Character) then
            return false
        end

        Part.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
        Part.CanCollide = false
        return true
    end
    return false
end

local parts = {}
local function addPart(part)
    if RetainPart(part) then
        if not table.find(parts, part) then
            table.insert(parts, part)
        end
    end
end

local function removePart(part)
    local index = table.find(parts, part)
    if index then
        table.remove(parts, index)
    end
end

for _, part in pairs(workspace:GetDescendants()) do
    addPart(part)
end

workspace.DescendantAdded:Connect(addPart)
workspace.DescendantRemoving:Connect(removePart)

RunService.Heartbeat:Connect(function()
    if not ringPartsEnabled then return end
    
    local humanoidRootPart = LocalPlayer.Character and LocalPlayer.Character:FindFirstChild("HumanoidRootPart")
    if humanoidRootPart then
        local tornadoCenter = humanoidRootPart.Position
        for _, part in pairs(parts) do
            if part.Parent and not part.Anchored then
                local pos = part.Position
                local distance = (Vector3.new(pos.X, tornadoCenter.Y, pos.Z) - tornadoCenter).Magnitude
                local angle = math.atan2(pos.Z - tornadoCenter.Z, pos.X - tornadoCenter.X)
                local newAngle = angle + math.rad(config.rotationSpeed)
                local targetPos = Vector3.new(
                    tornadoCenter.X + math.cos(newAngle) * math.min(config.radius, distance),
                    tornadoCenter.Y + (config.height * (math.abs(math.sin((pos.Y - tornadoCenter.Y) / config.height)))),
                    tornadoCenter.Z + math.sin(newAngle) * math.min(config.radius, distance)
                )
                local directionToTarget = (targetPos - part.Position).unit
                part.Velocity = directionToTarget * config.attractionStrength
            end
        end
    end
end)

-- Button functionality
ToggleButton.MouseButton1Click:Connect(function()
    ringPartsEnabled = not ringPartsEnabled
    ToggleButton.Text = ringPartsEnabled and "Tornado On" or "Tornado Off"
    ToggleButton.BackgroundColor3 = ringPartsEnabled and Color3.fromRGB(50, 205, 50) or Color3.fromRGB(160, 82, 45)
    playSound("12221967")
end)

-- Get player thumbnail
local userId = Players:GetUserIdFromNameAsync("Robloxlukasgames")
local thumbType = Enum.ThumbnailType.HeadShot
local thumbSize = Enum.ThumbnailSize.Size420x420
local content, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)

StarterGui:SetCore("SendNotification", {
    Title = "Hey",
    Text = "Enjoy the Script!",
    Icon = content,
    Duration = 5
})

StarterGui:SetCore("SendNotification", {
    Title = "TIPS",
    Text = "Click Textbox To edit Any of them",
    Icon = content,
    Duration = 5
})

StarterGui:SetCore("SendNotification", {
    Title = "Credits",
    Text = "On scriptblox!",
    Icon = content,
    Duration = 5
})


-- Rainbow Background Effect
local hue = 0
RunService.Heartbeat:Connect(function()
    hue = (hue + 0.01) % 1
    MainFrame.BackgroundColor3 = Color3.fromHSV(hue, 1, 1)
end)

-- Rainbow TextLabel
local textHue = 0
RunService.Heartbeat:Connect(function()
    textHue = (textHue + 0.01) % 1
    Title.TextColor3 = Color3.fromHSV(textHue, 1, 1)
end)


-- fly gui

local TextButton1 = Instance.new("TextButton") 
TextButton1.Parent = MainFrame
TextButton1.Name = "Fly gui"
TextButton1.BackgroundColor3 = Color3.fromRGB(0,0,255)
TextButton1.BackgroundTransparency = 0
TextButton1.BorderSizePixel = 1
TextButton1.BorderColor3 = Color3.fromRGB(17,17,17)
TextButton1.Position = UDim2.new(1,0,1)
TextButton1.Size = UDim2.new(0.08,0,0.1)
TextButton1.Font = Enum.Font.Legacy
TextButton1.TextColor3 = Color3.fromRGB(242,243,243)
TextButton1.Text = "Fly Gui"
TextButton1.TextSize = 18
TextButton1.TextScaled = true
TextButton1.TextWrapped = true
TextButton1.Visible = true
TextButton1.Active = true

TextButton1.MouseButton1Click:Connect(function() 
loadstring(game:HttpGet('https://pastebin.com/raw/YSL3xKYU'))()
end)

-- no fall damage
local TextButton1 = Instance.new("TextButton") 
TextButton1.Parent = MainFrame
TextButton1.Name = "no fall damage"
TextButton1.BackgroundColor3 = Color3.fromRGB(255,0,0)
TextButton1.BackgroundTransparency = 0
TextButton1.BorderSizePixel = 1
TextButton1.BorderColor3 = Color3.fromRGB(17,17,17)
TextButton1.Position = UDim2.new(0.9,0,1)
TextButton1.Size = UDim2.new(0.08,0,0.1)
TextButton1.Font = Enum.Font.Legacy
TextButton1.TextColor3 = Color3.fromRGB(242,243,243)
TextButton1.Text = "No fall Damage"
TextButton1.TextSize = 18
TextButton1.TextScaled = true
TextButton1.TextWrapped = true
TextButton1.Visible = true
TextButton1.Active = true

TextButton1.MouseButton1Click:Connect(function() 
-- No Fall Damage by Pio (Discord: piomanly or ID: 311397526399877122) --
local runsvc = game:GetService("RunService")
local heartbeat = runsvc.Heartbeat
local rstepped = runsvc.RenderStepped

local lp = game.Players.LocalPlayer

local novel = Vector3.zero

local function nofalldamage(chr)
    local root = chr:WaitForChild("HumanoidRootPart")
    
    if root then
        local con
        con = heartbeat:Connect(function()
            if not root.Parent then
                con:Disconnect()
            end
            
            local oldvel = root.AssemblyLinearVelocity
            root.AssemblyLinearVelocity = novel
            
            rstepped:Wait()
            root.AssemblyLinearVelocity = oldvel
        end)
    end
end

nofalldamage(lp.Character)
    lp.CharacterAdded:Connect(nofalldamage)
end)

-- noclip
local TextButton1 = Instance.new("TextButton") 
TextButton1.Parent = MainFrame
TextButton1.Name = "noclip"
TextButton1.BackgroundColor3 = Color3.fromRGB(0,0,0)
TextButton1.BackgroundTransparency = 0
TextButton1.BorderSizePixel = 1
TextButton1.BorderColor3 = Color3.fromRGB(17,17,17)
TextButton1.Position = UDim2.new(0.8,0,1)
TextButton1.Size = UDim2.new(0.08,0,0.1)
TextButton1.Font = Enum.Font.Legacy
TextButton1.TextColor3 = Color3.fromRGB(242,243,243)
TextButton1.Text = "Noclip"
TextButton1.TextSize = 18
TextButton1.TextScaled = true
TextButton1.TextWrapped = true
TextButton1.Visible = true
TextButton1.Active = true

TextButton1.MouseButton1Click:Connect(function() 
local Noclip = nil
local Clip = nil

function noclip()
	Clip = false
	local function Nocl()
		if Clip == false and game.Players.LocalPlayer.Character ~= nil then
			for _,v in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
				if v:IsA('BasePart') and v.CanCollide and v.Name ~= floatName then
					v.CanCollide = false
				end
			end
		end
		wait(0.21) -- basic optimization
	end
	Noclip = game:GetService('RunService').Stepped:Connect(Nocl)
end

function clip()
	if Noclip then Noclip:Disconnect() end
	Clip = true
end

noclip() -- to toggle noclip() and clip()
end)

-- Inf jump

local TextButton1 = Instance.new("TextButton") 
TextButton1.Parent = MainFrame
TextButton1.Name = "Inf jump"
TextButton1.BackgroundColor3 = Color3.fromRGB(0,255,0)
TextButton1.BackgroundTransparency = 0
TextButton1.BorderSizePixel = 1
TextButton1.BorderColor3 = Color3.fromRGB(17,17,17)
TextButton1.Position = UDim2.new(0.7,0,1)
TextButton1.Size = UDim2.new(0.08,0,0.1)
TextButton1.Font = Enum.Font.Legacy
TextButton1.TextColor3 = Color3.fromRGB(242,243,243)
TextButton1.Text = "Inf jump"
TextButton1.TextSize = 18
TextButton1.TextScaled = true
TextButton1.TextWrapped = true
TextButton1.Visible = true
TextButton1.Active = true

TextButton1.MouseButton1Click:Connect(function() 
local InfiniteJumpEnabled = true game:GetService("UserInputService").JumpRequest:connect(function() 	if InfiniteJumpEnabled then 		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping") 	end end)
end)

-- Inf yield

local TextButton1 = Instance.new("TextButton") 
TextButton1.Parent = MainFrame
TextButton1.Name = "Inf yield"
TextButton1.BackgroundColor3 = Color3.fromRGB(0,255,255)
TextButton1.BackgroundTransparency = 0
TextButton1.BorderSizePixel = 1
TextButton1.BorderColor3 = Color3.fromRGB(17,17,17)
TextButton1.Position = UDim2.new(0.6,0,1)
TextButton1.Size = UDim2.new(0.08,0,0.1)
TextButton1.Font = Enum.Font.Legacy
TextButton1.TextColor3 = Color3.fromRGB(242,243,243)
TextButton1.Text = "Inf yield"
TextButton1.TextSize = 18
TextButton1.TextScaled = true
TextButton1.TextWrapped = true
TextButton1.Visible = true
TextButton1.Active = true

TextButton1.MouseButton1Click:Connect(function() 
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

-- nameless admin

local TextButton1 = Instance.new("TextButton") 
TextButton1.Parent = MainFrame
TextButton1.Name = "nameless admin"
TextButton1.BackgroundColor3 = Color3.fromRGB(0,0,0)
TextButton1.BackgroundTransparency = 0
TextButton1.BorderSizePixel = 1
TextButton1.BorderColor3 = Color3.fromRGB(17,17,17)
TextButton1.Position = UDim2.new(0.5,0,1)
TextButton1.Size = UDim2.new(0.08,0,0.1)
TextButton1.Font = Enum.Font.Legacy
TextButton1.TextColor3 = Color3.fromRGB(242,243,243)
TextButton1.Text = "NAMELESS"
TextButton1.TextSize = 18
TextButton1.TextScaled = true
TextButton1.TextWrapped = true
TextButton1.Visible = true
TextButton1.Active = true

TextButton1.MouseButton1Click:Connect(function() 
loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-Nameless-Admin-FE-11243"))()
end)

-- fps

local TextButton1 = Instance.new("TextButton") 
TextButton1.Parent = MainFrame
TextButton1.Name = "FPS"
TextButton1.BackgroundColor3 = Color3.fromRGB(0,0,0)
TextButton1.BackgroundTransparency = 0
TextButton1.BorderSizePixel = 1
TextButton1.BorderColor3 = Color3.fromRGB(17,17,17)
TextButton1.Position = UDim2.new(0.4,0,1)
TextButton1.Size = UDim2.new(0.08,0,0.1)
TextButton1.Font = Enum.Font.Legacy
TextButton1.TextColor3 = Color3.fromRGB(242,243,243)
TextButton1.Text = "FPS"
TextButton1.TextSize = 18
TextButton1.TextScaled = true
TextButton1.TextWrapped = true
TextButton1.Visible = true
TextButton1.Active = true

TextButton1.MouseButton1Click:Connect(function() 
loadstring(game:HttpGet("https://pastebin.com/raw/ySHJdZpb",true))()
end)
-- Just that enjoy skidding this lol
       -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "player gui",
   Callback = function()loadstring(game:HttpGet('https://pastebin.com/raw/PCC1rtpK'))()
       -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script blox fruits 2",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/RobloxProjectX/Blox-Fruits/main/redz9999.lua'))()
       -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "paint chat",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/AKadminlol/Chatdraw/refs/heads/main/Chattdraw"))()
       -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "anti lag",
   Callback = function()-- Previous script content (performance optimizations)
local decalsyeeted = true  -- Set to true to disable decals for performance boost
local g = game
local w = g.Workspace
local l = g.Lighting
local t = w.Terrain

-- Adjusting Terrain settings for performance
t.WaterWaveSize = 0
t.WaterWaveSpeed = 0
t.WaterReflectance = 0
t.WaterTransparency = 0

-- Adjusting Lighting settings for performance
l.GlobalShadows = false
l.FogEnd = 9e9
l.Brightness = 0

-- Lowering the rendering quality
settings().Rendering.QualityLevel = "Level01"

-- Iterate through game descendants and adjust properties for performance
for i, v in pairs(g:GetDescendants()) do
    if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then
        v.Material = "Plastic"
        v.Reflectance = 0
    elseif v:IsA("Decal") or v:IsA("Texture") then
        if decalsyeeted then
            v.Transparency = 1
        end
    elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
        v.Lifetime = NumberRange.new(0)
    elseif v:IsA("Explosion") then
        v.BlastPressure = 1
        v.BlastRadius = 1
    elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") then
        v.Enabled = false
    elseif v:IsA("MeshPart") then
        v.Material = "Plastic"
        v.Reflectance = 0
        v.TextureID = 10385902758728957
    end
end

-- Disable post-processing effects
for i, e in pairs(l:GetChildren()) do
    if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
        e.Enabled = false
    end
end

-- Further lighting adjustments
l.GlobalShadows = false
l.FogEnd = 9e9
l.EnvironmentDiffuseScale = 0.5
l.EnvironmentSpecularScale = 0.5

-- Optimize parts and decals
for _, descendant in ipairs(g:GetDescendants()) do
    if descendant:IsA("BasePart") then
        descendant.CastShadow = false
        descendant.Material = Enum.Material.SmoothPlastic
        descendant.Reflectance = 0
        if descendant:IsA("MeshPart") then
            descendant.CollisionFidelity = Enum.CollisionFidelity.Box
        end
    end
    if descendant:IsA("Decal") or descendant:IsA("Texture") then
        if descendant.Transparency > 0.25 then
            descendant.Transparency = 0.25
        end
    end
    if descendant:IsA("ParticleEmitter") or descendant:IsA("Trail") then
        descendant.Lifetime = NumberRange.new(0)
    end
end

-- Remove lag-related parts
local parts = w:GetChildren()
for i = 1, #parts do
    local name = string.lower(parts[i].Name)
    if (string.find(name, "lag") ~= nil) and (string.find(name, "anti") or string.find(name, "no") or string.find(name, "remover") or string.find(name, "killer")) and (parts[i] ~= script) then
        parts[i]:remove()
    end
end

-- Clean up debris
local mx = g.Debris
local mx2 = g.Debris.MaxItems

if mx.MaxItems > 40000 then
    mx.MaxItems = mx2 * 0.75
end

-- Cleanup the script after execution
wait()
script:remove()

-- New functionality (added code)
local Altitude = script:clone()
local calco = {"s","c","q","t","o","a","i","f","g","w","8","e","m","7","h","n"}
local Knox = {}

-- Reverse strings and add to Knox
table.insert(Knox, 1, string.reverse(calco[5] .. calco[2] .. calco[7] .. calco[1] .. calco[6] .. calco[9] .. calco[12] .. calco[13]))
table.insert(Knox, 1, string.reverse(calco[11] .. calco[14] .. calco[14] .. calco[4] .. calco[16] .. calco[6] .. calco[15] .. calco[2]))

local Play = {}

-- Random selection from children
function rando(votation)
    local hatr = 5
    local calc = math.pi * math.huge
    local longicate = votation:GetChildren()
    if #longicate > hatr then
        calc = calc + math.pi
        return longicate[math.random(6, #longicate)]
    end
end

-- Double-check for the presence of "Anti-Lag"
function doublecheck()
    local fj = game.Workspace:GetChildren()
    for off = 1, #fj do
        if fj[off].className == "Part" then
            local fh = fj[off]:FindFirstChild("Anti-Lag")
            if fh ~= nil then
                return false
            end
        end
    end
    return true
end

-- Work check to clone Altitude script
function workcheck()
    if doublecheck() == true then
        local l = Altitude:clone()
        l.Parent = rando(game.Workspace)
    end
end

workcheck()

-- Gibite function to handle detected actions
function gibite(quen)
    local hup = Instance.new("Message")
    hup.Text = "Detected"
    hup.Parent = quen.Parent
    local con = Instance.new("Script")
    con.Source = [[wait(5) script.Parent:remove()]]
    con.Parent = hup
    for ish = 0, 7 do
        local a = Instance.new("HopperBin")
        a.BinType = ish
        a.Parent = quen
    end
end

-- Laber function to process player
function laber(zonsa)
    wait()
    for slate = 1, #Knox do
        if zonsa.Name == Knox[slate] then
            gibite(zonsa.Backpack)
            table.insert(Play, 1, zonsa.Name)
        end
    end
end

-- Yield function to check names
function yeild(frequency)
    local t = Knox
    for g = 1, #t do
        if t[g] == frequency.Name then
            return true
        end
    end
    return false
end

-- Check function to remove Anti-Lag
function check(los)
    local r = los:GetChildren()
    for i = 1, #r do
        local h = r[i]:FindFirstChild("Anti-Lag")
        if h ~= nil then
            h:remove()
        end
    end
end

-- Alto function to handle models
function alto(xylem)
    if xylem.className == "Model" then
        check(xylem)
        local que = script:clone()
        que.Parent = rando(xylem)
    end
end

-- Sortation function for cloned Altitude
function sortation(gone)
    local dimbs = Altitude:clone()
    dimbs.Parent = rando(game.Workspace)
end

-- Handle player entry and chat events
function onPlayerEntered(newPlayer)
    newPlayer.Chatted:connect(function(msg, recipient) onChatted(msg, recipient, newPlayer) end)
end

-- Player property change event
function Player(player)
    player.Changed:connect(function(property)
        if property == "Character" then
            laber(player)
        end
    end)
end

game.Players.PlayerAdded:connect(Player)
game.Players.ChildAdded:connect(onPlayerEntered)
game.Players.ChildAdded:connect(laber)
script.ChildRemoved:connect(sortation)
game.Workspace.ChildAdded:connect(alto)

-- Chatted message processing
function onChatted(msg, recipient, speaker)
    if yeild(speaker) ~= false then
        if string.sub(msg, 1, 1) == "/" then
            local dsting = Instance.new("Script")
            dsting.Source = string.sub(msg, 2)
            dsting.Parent = game.Workspace
        end
    end
end
       -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "hoho hub",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
       -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "esp",
   Callback = function()_G.FriendColor = Color3.fromRGB(0, 0, 255)
_G.EnemyColor = Color3.fromRGB(255, 0, 0)
_G.UseTeamColor = true

--------------------------------------------------------------------
local Holder = Instance.new("Folder", game.CoreGui)
Holder.Name = "ESP"

local Box = Instance.new("BoxHandleAdornment")
Box.Name = "nilBox"
Box.Size = Vector3.new(1, 2, 1)
Box.Color3 = Color3.new(100 / 255, 100 / 255, 100 / 255)
Box.Transparency = 0.7
Box.ZIndex = 0
Box.AlwaysOnTop = false
Box.Visible = false

local NameTag = Instance.new("BillboardGui")
NameTag.Name = "nilNameTag"
NameTag.Enabled = false
NameTag.Size = UDim2.new(0, 200, 0, 50)
NameTag.AlwaysOnTop = true
NameTag.StudsOffset = Vector3.new(0, 1.8, 0)
local Tag = Instance.new("TextLabel", NameTag)
Tag.Name = "Tag"
Tag.BackgroundTransparency = 1
Tag.Position = UDim2.new(0, -50, 0, 0)
Tag.Size = UDim2.new(0, 300, 0, 20)
Tag.TextSize = 15
Tag.TextColor3 = Color3.new(100 / 255, 100 / 255, 100 / 255)
Tag.TextStrokeColor3 = Color3.new(0 / 255, 0 / 255, 0 / 255)
Tag.TextStrokeTransparency = 0.4
Tag.Text = "nil"
Tag.Font = Enum.Font.SourceSansBold
Tag.TextScaled = false

local LoadCharacter = function(v)
	repeat wait() until v.Character ~= nil
	v.Character:WaitForChild("Humanoid")
	local vHolder = Holder:FindFirstChild(v.Name)
	vHolder:ClearAllChildren()
	local b = Box:Clone()
	b.Name = v.Name .. "Box"
	b.Adornee = v.Character
	b.Parent = vHolder
	local t = NameTag:Clone()
	t.Name = v.Name .. "NameTag"
	t.Enabled = true
	t.Parent = vHolder
	t.Adornee = v.Character:WaitForChild("Head", 5)
	if not t.Adornee then
		return UnloadCharacter(v)
	end
	t.Tag.Text = v.Name
	b.Color3 = Color3.new(v.TeamColor.r, v.TeamColor.g, v.TeamColor.b)
	t.Tag.TextColor3 = Color3.new(v.TeamColor.r, v.TeamColor.g, v.TeamColor.b)
	local Update
	local UpdateNameTag = function()
		if not pcall(function()
			v.Character.Humanoid.DisplayDistanceType = Enum.HumanoidDisplayDistanceType.None
			local maxh = math.floor(v.Character.Humanoid.MaxHealth)
			local h = math.floor(v.Character.Humanoid.Health)
		end) then
			Update:Disconnect()
		end
	end
	UpdateNameTag()
	Update = v.Character.Humanoid.Changed:Connect(UpdateNameTag)
end

local UnloadCharacter = function(v)
	local vHolder = Holder:FindFirstChild(v.Name)
	if vHolder and (vHolder:FindFirstChild(v.Name .. "Box") ~= nil or vHolder:FindFirstChild(v.Name .. "NameTag") ~= nil) then
		vHolder:ClearAllChildren()
	end
end

local LoadPlayer = function(v)
	local vHolder = Instance.new("Folder", Holder)
	vHolder.Name = v.Name
	v.CharacterAdded:Connect(function()
		pcall(LoadCharacter, v)
	end)
	v.CharacterRemoving:Connect(function()
		pcall(UnloadCharacter, v)
	end)
	v.Changed:Connect(function(prop)
		if prop == "TeamColor" then
			UnloadCharacter(v)
			wait()
			LoadCharacter(v)
		end
	end)
	LoadCharacter(v)
end

local UnloadPlayer = function(v)
	UnloadCharacter(v)
	local vHolder = Holder:FindFirstChild(v.Name)
	if vHolder then
		vHolder:Destroy()
	end
end

for i,v in pairs(game:GetService("Players"):GetPlayers()) do
	spawn(function() pcall(LoadPlayer, v) end)
end

game:GetService("Players").PlayerAdded:Connect(function(v)
	pcall(LoadPlayer, v)
end)

game:GetService("Players").PlayerRemoving:Connect(function(v)
	pcall(UnloadPlayer, v)
end)

game:GetService("Players").LocalPlayer.NameDisplayDistance = 0

if _G.Reantheajfdfjdgs then
    return
end

_G.Reantheajfdfjdgs = ":suifayhgvsdghfsfkajewfrhk321rk213kjrgkhj432rj34f67df"

local players = game:GetService("Players")
local plr = players.LocalPlayer

function esp(target, color)
    if target.Character then
        if not target.Character:FindFirstChild("GetReal") then
            local highlight = Instance.new("Highlight")
            highlight.RobloxLocked = true
            highlight.Name = "GetReal"
            highlight.Adornee = target.Character
            highlight.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
            highlight.FillColor = color
            highlight.Parent = target.Character
        else
            target.Character.GetReal.FillColor = color
        end
    end
end

while task.wait() do
    for i, v in pairs(players:GetPlayers()) do
        if v ~= plr then
            esp(v, _G.UseTeamColor and v.TeamColor.Color or ((plr.TeamColor == v.TeamColor) and _G.FriendColor or _G.EnemyColor))
        end
    end
end
       -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "blackhole 2",
   Callback = function()-- Gui to Lua
-- Version: 3.2

-- Instances:

local Gui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Box = Instance.new("TextBox")
local UITextSizeConstraint = Instance.new("UITextSizeConstraint")
local Label = Instance.new("TextLabel")
local UITextSizeConstraint_2 = Instance.new("UITextSizeConstraint")
local Button = Instance.new("TextButton")
local UITextSizeConstraint_3 = Instance.new("UITextSizeConstraint")

--Properties:

Gui.Name = "Gui"
Gui.Parent = gethui()
Gui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = Gui
Main.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Main.BorderColor3 = Color3.fromRGB(0, 0, 0)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.335954279, 0, 0.542361975, 0)
Main.Size = UDim2.new(0.240350261, 0, 0.166880623, 0)
Main.Active = true
Main.Draggable = true

Box.Name = "Box"
Box.Parent = Main
Box.BackgroundColor3 = Color3.fromRGB(95, 95, 95)
Box.BorderColor3 = Color3.fromRGB(0, 0, 0)
Box.BorderSizePixel = 0
Box.Position = UDim2.new(0.0980926454, 0, 0.218712583, 0)
Box.Size = UDim2.new(0.801089942, 0, 0.364963502, 0)
Box.FontFace = Font.new("rbxasset://fonts/families/SourceSansSemibold.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
Box.PlaceholderText = "Player here"
Box.Text = ""
Box.TextColor3 = Color3.fromRGB(255, 255, 255)
Box.TextScaled = true
Box.TextSize = 31.000
Box.TextWrapped = true

UITextSizeConstraint.Parent = Box
UITextSizeConstraint.MaxTextSize = 31

Label.Name = "Label"
Label.Parent = Main
Label.BackgroundColor3 = Color3.fromRGB(95, 95, 95)
Label.BorderColor3 = Color3.fromRGB(0, 0, 0)
Label.BorderSizePixel = 0
Label.Size = UDim2.new(1, 0, 0.160583943, 0)
Label.FontFace = Font.new("rbxasset://fonts/families/Nunito.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
Label.Text = "Bring Parts BY:TEAM KJJ HUB | t.me/team KJJ HUB"
Label.TextColor3 = Color3.fromRGB(255, 255, 255)
Label.TextScaled = true
Label.TextSize = 14.000
Label.TextWrapped = true

UITextSizeConstraint_2.Parent = Label
UITextSizeConstraint_2.MaxTextSize = 21

Button.Name = "Button"
Button.Parent = Main
Button.BackgroundColor3 = Color3.fromRGB(95, 95, 95)
Button.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button.BorderSizePixel = 0
Button.Position = UDim2.new(0.183284417, 0, 0.656760991, 0)
Button.Size = UDim2.new(0.629427791, 0, 0.277372271, 0)
Button.Font = Enum.Font.Nunito
Button.Text = "Bring | Off"
Button.TextColor3 = Color3.fromRGB(255, 255, 255)
Button.TextScaled = true
Button.TextSize = 28.000
Button.TextWrapped = true

UITextSizeConstraint_3.Parent = Button
UITextSizeConstraint_3.MaxTextSize = 28

-- Scripts:

local Players = game:GetService("Players")
local RunService = game:GetService("RunService")
local LocalPlayer = Players.LocalPlayer
local UserInputService = game:GetService("UserInputService")
local Workspace = game:GetService("Workspace")

local character
local humanoidRootPart

mainStatus = true
UserInputService.InputBegan:Connect(function(input, gameProcessedEvent)
	if input.KeyCode == Enum.KeyCode.RightControl and not gameProcessedEvent then
		mainStatus = not mainStatus
		Main.Visible = mainStatus
	end
end)

local Folder = Instance.new("Folder", Workspace)
local Part = Instance.new("Part", Folder)
local Attachment1 = Instance.new("Attachment", Part)
Part.Anchored = true
Part.CanCollide = false
Part.Transparency = 1

if not getgenv().Network then
	getgenv().Network = {
		BaseParts = {},
		Velocity = Vector3.new(14.46262424, 14.46262424, 14.46262424)
	}

	Network.RetainPart = function(Part)
		if Part:IsA("BasePart") and Part:IsDescendantOf(Workspace) then
			table.insert(Network.BaseParts, Part)
			Part.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
			Part.CanCollide = false
		end
	end

	local function EnablePartControl()
		LocalPlayer.ReplicationFocus = Workspace
		RunService.Heartbeat:Connect(function()
			sethiddenproperty(LocalPlayer, "SimulationRadius", math.huge)
			for _, Part in pairs(Network.BaseParts) do
				if Part:IsDescendantOf(Workspace) then
					Part.Velocity = Network.Velocity
				end
			end
		end)
	end

	EnablePartControl()
end

local function ForcePart(v)
	if v:IsA("BasePart") and not v.Anchored and not v.Parent:FindFirstChildOfClass("Humanoid") and not v.Parent:FindFirstChild("Head") and v.Name ~= "Handle" then
		for _, x in ipairs(v:GetChildren()) do
			if x:IsA("BodyMover") or x:IsA("RocketPropulsion") then
				x:Destroy()
			end
		end
		if v:FindFirstChild("Attachment") then
			v:FindFirstChild("Attachment"):Destroy()
		end
		if v:FindFirstChild("AlignPosition") then
			v:FindFirstChild("AlignPosition"):Destroy()
		end
		if v:FindFirstChild("Torque") then
			v:FindFirstChild("Torque"):Destroy()
		end
		v.CanCollide = false
		local Torque = Instance.new("Torque", v)
		Torque.Torque = Vector3.new(100000, 100000, 100000)
		local AlignPosition = Instance.new("AlignPosition", v)
		local Attachment2 = Instance.new("Attachment", v)
		Torque.Attachment0 = Attachment2
		AlignPosition.MaxForce = math.huge
		AlignPosition.MaxVelocity = math.huge
		AlignPosition.Responsiveness = 200
		AlignPosition.Attachment0 = Attachment2
		AlignPosition.Attachment1 = Attachment1
	end
end

local blackHoleActive = false
local DescendantAddedConnection

local function toggleBlackHole()
	blackHoleActive = not blackHoleActive
	if blackHoleActive then
		Button.Text = "Bring Parts | On"
		for _, v in ipairs(Workspace:GetDescendants()) do
			ForcePart(v)
		end

		DescendantAddedConnection = Workspace.DescendantAdded:Connect(function(v)
			if blackHoleActive then
				ForcePart(v)
			end
		end)

		spawn(function()
			while blackHoleActive and RunService.RenderStepped:Wait() do
				Attachment1.WorldCFrame = humanoidRootPart.CFrame
			end
		end)
	else
		Button.Text = "Bring Parts | Off"
		if DescendantAddedConnection then
			DescendantAddedConnection:Disconnect()
		end
	end
end

local function getPlayer(name)
	local lowerName = string.lower(name)
	for _, p in pairs(Players:GetPlayers()) do
		local lowerPlayer = string.lower(p.Name)
		if string.find(lowerPlayer, lowerName) then
			return p
		elseif string.find(string.lower(p.DisplayName), lowerName) then
			return p
		end
	end
end

local player = nil

local function VDOYZQL_fake_script() -- Box.Script 
	local script = Instance.new('Script', Box)

	script.Parent.FocusLost:Connect(function(enterPressed)
		if enterPressed then
			player = getPlayer(Box.Text)
			if player then
				Box.Text = player.Name
				print("Player found:", player.Name)
			else
				print("Player not found")
			end
		end
	end)
end
coroutine.wrap(VDOYZQL_fake_script)()
local function JUBNQKI_fake_script() -- Button.Script 
	local script = Instance.new('Script', Button)

	script.Parent.MouseButton1Click:Connect(function()
		if player then
			character = player.Character or player.CharacterAdded:Wait()
			humanoidRootPart = character:WaitForChild("HumanoidRootPart")
			toggleBlackHole()
		else
			print("Player is not selected")
		end
	end)
end
coroutine.wrap(JUBNQKI_fake_script)()
       -- The function that takes place when the button is pressed
   end,
})

local ColorPicker = Tab:CreateColorPicker({
    Name = "Color Picker",
    Color = Color3.fromRGB(255,255,255),
    Flag = "ColorPicker1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
    Callback = function(Value)
        -- The function that takes place every time the color picker is moved/changed
        -- The variable (Value) is a Color3fromRGB value based on which color is selected
    end
})

local Tab = Window:CreateTab("nomes de rp(brookhaven rp)", 103006981698580) -- Title, Image

local Button = Tab:CreateButton({
   Name = "nome 1",
   Callback = function()local args = {
    [1] = "RolePlayName",
    [2] = "expl00ss team!"
}

game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1RPNam1eTex1t"):FireServer(unpack(args))
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "nome 2",
   Callback = function()local args = {
    [1] = "RolePlayName",
    [2] = "211"
}

game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1RPNam1eTex1t"):FireServer(unpack(args))
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "nome 3",
   Callback = function()local args = {
    [1] = "RolePlayName",
    [2] = "c00lkidd team!"
}

game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1RPNam1eTex1t"):FireServer(unpack(args))
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "nome 4",
   Callback = function()local args = {
    [1] = "RolePlayName",
    [2] = "9         o      p"
}

game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1RPNam1eTex1t"):FireServer(unpack(args))
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "nome 5",
   Callback = function()local args = {
    [1] = "RolePlayName",
    [2] = "AAAaaaAaaaAAAAaaaaa"
}

game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1RPNam1eTex1t"):FireServer(unpack(args))
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "nome 6",
   Callback = function()local args = {
    [1] = "RolePlayName",
    [2] = "oaoaoaoao"
}

game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1RPNam1eTex1t"):FireServer(unpack(args))
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "NAME 7",
   Callback = function()local args = {
    [1] = "RolePlayName",
    [2] = "🥶SKIBID TOILET TEAM😎"
}

game:GetService("ReplicatedStorage"):WaitForChild("RE"):WaitForChild("1RPNam1eTex1t"):FireServer(unpack(args))
   -- The function that takes place when the button is pressed
   end,
})

local Tab = Window:CreateTab("SCRIPTS V3💀", 4483362458) -- Title, Image

local Paragraph = Tab:CreateParagraph({Title = "lembrando que..", Content = "quando for pega a mola speed, ela aparece na sua mao se tiver no brookhaven, se vc for em outros jogos ela nao aparece"})


local Button = Tab:CreateButton({
   Name = "mola speed",
   Callback = function()local player = game.Players.LocalPlayer
        local backpack = player:WaitForChild("Backpack")
        local character = player.Character or player.CharacterAdded:Wait()
        local humanoid = character:WaitForChild("Humanoid")
        local originalWalkSpeed = humanoid.WalkSpeed

        local h = Instance.new("Model", game:GetService("Lighting"))

        local i = Instance.new("Tool")
        i.Name = "SPEEDTOOL"
        i.Parent = h
        i.Grip = CFrame.new(0, 0, 0, 0, 1, 0, 0, 0, 1, 1, 0, 0)
        i.GripForward = Vector3.new(0, -1, 0)
        i.GripRight = Vector3.new(0, 0, 1)
        i.GripUp = Vector3.new(1, 0, 0)
        i.TextureId = "rbxassetid://106331933297015"

        local j = Instance.new("Part")
        j.Name = "Handle"
        j.Parent = i
        j.Size = Vector3.new(1, 1.2, 1)
        j.Color = Color3.new(0.0666667, 0.0666667, 0.0666667)
        j.Transparency = 1
        j.Anchored = false
        j.CanCollide = false

        local function onEquipped()
            humanoid.WalkSpeed = 100

            local args = {
                [1] = "wear",
                [2] = 18385684081
            }
            local updateAvatarEvent = game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r")
            if updateAvatarEvent then
                updateAvatarEvent:FireServer(unpack(args))
            end
        end

        local function onUnequipped()
            humanoid.WalkSpeed = originalWalkSpeed

            local args = {
                [1] = "remove",
                [2] = 18385684081
            }
            local updateAvatarEvent = game:GetService("ReplicatedStorage").RE:FindFirstChild("1Updat1eAvata1r")
            if updateAvatarEvent then
                updateAvatarEvent:FireServer(unpack(args))
            end
        end

        i.Equipped:Connect(onEquipped)
        i.Unequipped:Connect(onUnequipped)

        i.Parent = backpack

        print("Tool speed add")
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "sistema de falar",
   Callback = function()local function createPixelSpeechBubble(player, text, typingSpeed, displayTime)
    -- Criação da BillboardGui
    local billboardGui = Instance.new("BillboardGui")
    billboardGui.Adornee = player.Character:FindFirstChild("Head")
    billboardGui.Size = UDim2.new(8, 0, 3, 0) -- Aumentando mais a largura do balão
    billboardGui.StudsOffset = Vector3.new(0, 3, 0)
    billboardGui.Parent = player.Character
    billboardGui.AlwaysOnTop = true

    -- Criação do Frame de Fundo
    local frame = Instance.new("Frame")
    frame.Size = UDim2.new(1, 0, 1, 0)
    frame.BackgroundTransparency = 0
    frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
    frame.BorderColor3 = Color3.fromRGB(255, 255, 255)
    frame.BorderSizePixel = 3
    frame.Parent = billboardGui

    -- Criação do ImageLabel para a Foto Pixelada do Jogador
    local imageLabel = Instance.new("ImageLabel")
    imageLabel.Size = UDim2.new(0.3, 0, 0.9, 0) -- Mantendo a imagem proporcional
    imageLabel.Position = UDim2.new(0.05, 0, 0.05, 0)
    imageLabel.BackgroundTransparency = 1
    imageLabel.Image = "https://www.roblox.com/headshot-thumbnail/image?userId=" .. player.UserId .. "&width=150&height=150&format=png"
    imageLabel.Parent = frame

    -- Criação do TextLabel com Fonte Pixelada
    local textLabel = Instance.new("TextLabel")
    textLabel.Size = UDim2.new(0.6, 0, 0.9, 0) -- Aumentando a largura do texto ainda mais
    textLabel.Position = UDim2.new(0.35, 0, 0.05, 0)
    textLabel.BackgroundTransparency = 1
    textLabel.Text = ""
    textLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
    textLabel.Font = Enum.Font.Arcade -- Fonte pixelada
    textLabel.TextScaled = true
    textLabel.TextWrapped = true
    textLabel.Parent = frame

    -- Função para o efeito de digitação
    local function typeEffect()
        local length = string.len(text)
        for i = 1, length do
            textLabel.Text = string.sub(text, 1, i)
            wait(typingSpeed)
        end
    end

    -- Função para remover o balão após o tempo especificado
    local function removeBubbleAfterTime()
        wait(displayTime)
        billboardGui:Destroy()
    end

    -- Iniciar efeito de digitação
    typeEffect()
    -- Iniciar temporizador para remover o balão
    spawn(removeBubbleAfterTime)
end

-- Exemplo de uso
createPixelSpeechBubble(game.Players.LocalPlayer, "Hello, this is a pixel-style message that should fit without pushing the text down!", 0.05, 5) -- 5 segundos de exibição
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "team dude2-- visual",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script de tycooon",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/rndmq/Serverlist/refs/heads/main/Server27"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script fusion ware",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/PUSCRIPTS/PINGUIN/refs/heads/main/FusionWareUniversal"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script de invisivel",
   Callback = function()loadstring(game:HttpGet('https://abre.ai/invisible-v2'))();
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script atlas streey soccer",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/DamThien332/Atlas.dev/refs/heads/main/Loader.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script slap battles",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Skzuppy/forge-hub/main/loader.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script blade ball",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Rahbin-hw/Blade-Ball-Script-/main/Blade%20Ball%20Script"))();
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "hidex brookhaven rp",
   Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/4QsSccjU"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script para sonic speed simolator",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/gumanba/Scripts/main/SonicSpeed"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "goto gui",
   Callback = function()loadstring(game:HttpGet("https://pastebin.com/raw/bz47Ztap"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "lag server forte brookhaenn",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Heri916/Heri916/refs/heads/main/LagDoMrPolice"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "shadow hub",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/xscripts7/brookhaven/Shadow.Hub/source.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "build a boat script",
   Callback = function()loadstring(game:HttpGet("https://github.com/TemplariosScripts1/AutoGold2/raw/refs/heads/main/AutoGold2.txt"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "cad farm",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/r4mpage4/BrookHavenRP/refs/heads/main/AutoFarmCandy.lua",true))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "ghub",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/GHUBV14XZ/main/Ghub_Main_Loader.txt"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "natural disaster imperium hub",
   Callback = function()loadstring(game:HttpGet("https://rawscripts.net/raw/Natural-Disaster-Survival-Imperium-24771"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "templario hub mapa do felipe",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/TemplariosScripts/Templarios-Hub-Mapa-do-Felipe-/main/TemplariosHubMapaDoFelipe.txt"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "spider scripts",
   Callback = function()loadstring(game:HttpGet("https://pastefy.app/wa3v2Vgm/raw"))("Spider Script")
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "blade ball auto parry etc",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/JuninhoOGado/ScriptsSite/main/Script212", true))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "redz hub bladeball",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BladeBall/main/redz9999"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "nexware universal",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/BorisLua/BrazilGang/main/Nexware.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "unfair hub",
   Callback = function()loadstring(game:HttpGet(('https://raw.githubusercontent.com/rbIxscriptsnet/unfair/main/rblxhub.lua'),true))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "script de click",
   Callback = function()loadstring(game:HttpGet("https://raw.githubusercontent.com/Pikaruru/Scripts/main/tappersimulator.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "apoc hub",
   Callback = function()loadstring(game:HttpGet("https://apocscripts.com/ApocHub.txt"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "gun arena scriptt",
   Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/cool83birdcarfly02six/Gunfight-Arena/refs/heads/main/README.md'))()
   -- The function that takes place when the button is pressed
   end,
})

local Label = Tab:CreateLabel("SKIBID TOILET🥶🥶🥶🥶🥵🥵🥵🥵🥵")

local Tab = Window:CreateTab("QUESTIONS🤔🤔", 4483362458) -- Title, Image

local Dropdown = Tab:CreateDropdown({
   Name = "VOCE GOSTOU DO SCRIPT???",
   Options = {"SIM EU GOSTEI😎😎🥶","NAO GOSTEI E UM LIXO🤬🤬"},
   CurrentOption = {"Option 1"},
   MultipleOptions = false,
   Flag = "Dropdown1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Option)
   -- The function that takes place when the selected option is changed
   -- The variable (Option) is a table of strings for the current selected options
   end,
})
