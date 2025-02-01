-- biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

-- janela principal

local Window = Fluent:CreateWindow({
    Title = "Cael hub" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

-- Abas

local Tabs = {
    Main = Window:AddTab({ Title = "Inicio" }),
    keys = Window:AddTab({ Title = "scripts com keys" }),
    bons = Window:AddTab({ Title = "Scripts bom" }),
    Settings = Window:AddTab({ Title = "Configurações", Icon = "settings" })
}

-- notificacao

Fluent:Notify({ Title = "Notificação", Content = "script executado com sucesso " })
Fluent:Notify({ Title = "Diga-me no Instagram", Content = "Eai ja está conectado nas redes sociais do cael?" })
Fluent:Notify({ Title = "Instagram", Content = "Siga no Instagram (carlosdanielsilv708" })
Fluent:Notify({ Title = "keys dos Scripts", Content = "Key:Graciasporseleccionarnos, Key:</>FaseTesting" })
Fluent:Notify({ Title = "Leia", Content = "Fase de teste⚠️" })
Fluent:Notify({ Title = "Leia", Content = "Se quiser que eu faça um script pra você fale comigo não cobro nada👍" })
-- paragrafo

    Tabs.Main:AddParagraph({
        Title = "Cael hub",
        Content = "começando no ramo de script 👍"
    })

-- botao

Tabs.Main:AddButton({ Title = "shadow", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/xscripts7/XScripts/refs/heads/XScript/ShadowHub", true))() end })
Tabs.keys:AddButton({ Title = "dopamina", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Dopamina-Hub-17894"))() end })
Tabs.keys:AddButton({ Title = "Cael sky", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/yofriendfromschool1/Sky-Hub/main/SkyHub.txt"))()end })
Tabs.Main:AddButton({ Title = "sander X", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/New.lua'))() end })
Tabs.Main:AddButton({ Title = "carl hub versão beta", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/carlosdaniel987/Carlos/refs/heads/main/README.md"))() end })
Tabs.bons:AddButton({ Title = "Sirius", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Sirius-7420"))() end })
