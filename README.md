local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "THIAGO SCRIPT",
   LoadingTitle = "Carregando Painel",
   LoadingSubtitle = "by Thiago",
   ConfigurationSaving = {
      Enabled = false
   }
})

-- Criar uma aba
local MainTab = Window:CreateTab("Principal", 4483362458)

-- Botão para executar seu script
local RunScript = MainTab:CreateButton({
   Name = "Executar Script",
   Callback = function()
       loadstring(game:HttpGet("https://pastefy.app/TnWWJ4NS/raw"))()
   end,
})
