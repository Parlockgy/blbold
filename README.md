-- GUI to Lua 
-- Version: 0.0.3

-- Instances:

local Hackgui = Instance.new("Frame")
local UIStroke_1 = Instance.new("UIStroke")
local menu_1 = Instance.new("TextLabel")
local UIStroke_2 = Instance.new("UIStroke")
local Skybutton_1 = Instance.new("TextButton")
local UIStroke_3 = Instance.new("UIStroke")
local UIStroke_4 = Instance.new("UIStroke")
local Messagebutton_1 = Instance.new("TextButton")
local UIStroke_5 = Instance.new("UIStroke")
local UIStroke_6 = Instance.new("UIStroke")
local Leavebutton_1 = Instance.new("TextButton")
local UIStroke_7 = Instance.new("UIStroke")
local UIStroke_8 = Instance.new("UIStroke")
local Texturebutton_1 = Instance.new("TextButton")
local UIStroke_9 = Instance.new("UIStroke")
local UIStroke_10 = Instance.new("UIStroke")
local Lagbutton_1 = Instance.new("TextButton")
local UIStroke_11 = Instance.new("UIStroke")
local UIStroke_12 = Instance.new("UIStroke")
local Spambutton_1 = Instance.new("TextButton")
local UIStroke_13 = Instance.new("UIStroke")
local UIStroke_14 = Instance.new("UIStroke")
local Loopkillbutton_1 = Instance.new("TextButton")
local UIStroke_15 = Instance.new("UIStroke")
local UIStroke_16 = Instance.new("UIStroke")
local kickall_1 = Instance.new("TextButton")
local UIStroke_17 = Instance.new("UIStroke")
local UIStroke_18 = Instance.new("UIStroke")

-- Properties:
Hackgui.Name = "Hackgui"
Hackgui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Hackgui.BackgroundColor3 = Color3.fromRGB(99,99,249)
Hackgui.BorderColor3 = Color3.fromRGB(0,0,0)
Hackgui.BorderSizePixel = 0
Hackgui.Position = UDim2.new(0.389027417, 0,0.235772356, 0)
Hackgui.Size = UDim2.new(0, 270,0, 259)

UIStroke_1.Parent = Hackgui
UIStroke_1.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_1.Thickness = 3

menu_1.Name = "menu"
menu_1.Parent = Hackgui
menu_1.BackgroundColor3 = Color3.fromRGB(255,255,255)
menu_1.BackgroundTransparency = 1
menu_1.BorderColor3 = Color3.fromRGB(0,0,0)
menu_1.BorderSizePixel = 0
menu_1.Position = UDim2.new(0.0360857062, 0,-0.000722052995, 0)
menu_1.Size = UDim2.new(0, 179,0, 33)
menu_1.Font = Enum.Font.Unknown
menu_1.Text = "BLUUDUD Gui"
menu_1.TextColor3 = Color3.fromRGB(255,255,255)
menu_1.TextScaled = true
menu_1.TextSize = 14
menu_1.TextWrapped = true

UIStroke_2.Parent = menu_1
UIStroke_2.Thickness = 3

Skybutton_1.Name = "Skybutton"
Skybutton_1.Parent = Hackgui
Skybutton_1.Active = true
Skybutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Skybutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Skybutton_1.BorderSizePixel = 0
Skybutton_1.Position = UDim2.new(0.0324189365, 0,0.158811241, 0)
Skybutton_1.Size = UDim2.new(0, 118,0, 18)
Skybutton_1.Font = Enum.Font.Unknown
Skybutton_1.Text = "Change Sky"
Skybutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Skybutton_1.TextScaled = true
Skybutton_1.TextSize = 14
Skybutton_1.TextWrapped = true

UIStroke_3.Parent = Skybutton_1
UIStroke_3.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_3.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_3.Thickness = 3

UIStroke_4.Parent = Skybutton_1
UIStroke_4.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_4.Thickness = 2

Messagebutton_1.Name = "Messagebutton"
Messagebutton_1.Parent = Hackgui
Messagebutton_1.Active = true
Messagebutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Messagebutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Messagebutton_1.BorderSizePixel = 0
Messagebutton_1.Position = UDim2.new(0.524217367, 0,0.158811241, 0)
Messagebutton_1.Size = UDim2.new(0, 118,0, 18)
Messagebutton_1.Font = Enum.Font.Unknown
Messagebutton_1.Text = "Hacking Message"
Messagebutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Messagebutton_1.TextScaled = true
Messagebutton_1.TextSize = 14
Messagebutton_1.TextWrapped = true

UIStroke_5.Parent = Messagebutton_1
UIStroke_5.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_5.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_5.Thickness = 3

UIStroke_6.Parent = Messagebutton_1
UIStroke_6.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_6.Thickness = 2

Leavebutton_1.Name = "Leavebutton"
Leavebutton_1.Parent = Hackgui
Leavebutton_1.Active = true
Leavebutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Leavebutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Leavebutton_1.BorderSizePixel = 0
Leavebutton_1.Position = UDim2.new(0.0324189365, 0,0.263058335, 0)
Leavebutton_1.Size = UDim2.new(0, 118,0, 18)
Leavebutton_1.Font = Enum.Font.Unknown
Leavebutton_1.Text = "Impossible Leave"
Leavebutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Leavebutton_1.TextScaled = true
Leavebutton_1.TextSize = 14
Leavebutton_1.TextWrapped = true

UIStroke_7.Parent = Leavebutton_1
UIStroke_7.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_7.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_7.Thickness = 3

UIStroke_8.Parent = Leavebutton_1
UIStroke_8.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_8.Thickness = 2

Texturebutton_1.Name = "Texturebutton"
Texturebutton_1.Parent = Hackgui
Texturebutton_1.Active = true
Texturebutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Texturebutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Texturebutton_1.BorderSizePixel = 0
Texturebutton_1.Position = UDim2.new(0.521307826, 0,0.263058335, 0)
Texturebutton_1.Size = UDim2.new(0, 118,0, 18)
Texturebutton_1.Font = Enum.Font.Unknown
Texturebutton_1.Text = "Textures Changer"
Texturebutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Texturebutton_1.TextScaled = true
Texturebutton_1.TextSize = 14
Texturebutton_1.TextWrapped = true

UIStroke_9.Parent = Texturebutton_1
UIStroke_9.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_9.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_9.Thickness = 3

UIStroke_10.Parent = Texturebutton_1
UIStroke_10.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_10.Thickness = 2

Lagbutton_1.Name = "Lagbutton"
Lagbutton_1.Parent = Hackgui
Lagbutton_1.Active = true
Lagbutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Lagbutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Lagbutton_1.BorderSizePixel = 0
Lagbutton_1.Position = UDim2.new(0.0324189365, 0,0.367305458, 0)
Lagbutton_1.Size = UDim2.new(0, 118,0, 18)
Lagbutton_1.Font = Enum.Font.Unknown
Lagbutton_1.Text = "Lag Game"
Lagbutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Lagbutton_1.TextScaled = true
Lagbutton_1.TextSize = 14
Lagbutton_1.TextWrapped = true

UIStroke_11.Parent = Lagbutton_1
UIStroke_11.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_11.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_11.Thickness = 3

UIStroke_12.Parent = Lagbutton_1
UIStroke_12.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_12.Thickness = 2

Spambutton_1.Name = "Spambutton"
Spambutton_1.Parent = Hackgui
Spambutton_1.Active = true
Spambutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Spambutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Spambutton_1.BorderSizePixel = 0
Spambutton_1.Position = UDim2.new(0.521307826, 0,0.367305458, 0)
Spambutton_1.Size = UDim2.new(0, 118,0, 18)
Spambutton_1.Font = Enum.Font.Unknown
Spambutton_1.Text = "Spam Chat"
Spambutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Spambutton_1.TextScaled = true
Spambutton_1.TextSize = 14
Spambutton_1.TextWrapped = true

UIStroke_13.Parent = Spambutton_1
UIStroke_13.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_13.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_13.Thickness = 3

UIStroke_14.Parent = Spambutton_1
UIStroke_14.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_14.Thickness = 2

Loopkillbutton_1.Name = "Loopkillbutton"
Loopkillbutton_1.Parent = Hackgui
Loopkillbutton_1.Active = true
Loopkillbutton_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
Loopkillbutton_1.BorderColor3 = Color3.fromRGB(0,0,0)
Loopkillbutton_1.BorderSizePixel = 0
Loopkillbutton_1.Position = UDim2.new(0.0324189365, 0,0.463830531, 0)
Loopkillbutton_1.Size = UDim2.new(0, 118,0, 18)
Loopkillbutton_1.Font = Enum.Font.Unknown
Loopkillbutton_1.Text = "Loopkill All"
Loopkillbutton_1.TextColor3 = Color3.fromRGB(255,255,255)
Loopkillbutton_1.TextScaled = true
Loopkillbutton_1.TextSize = 14
Loopkillbutton_1.TextWrapped = true

UIStroke_15.Parent = Loopkillbutton_1
UIStroke_15.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_15.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_15.Thickness = 3

UIStroke_16.Parent = Loopkillbutton_1
UIStroke_16.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_16.Thickness = 2

kickall_1.Name = "kickall"
kickall_1.Parent = Hackgui
kickall_1.Active = true
kickall_1.BackgroundColor3 = Color3.fromRGB(131,106,255)
kickall_1.BorderColor3 = Color3.fromRGB(0,0,0)
kickall_1.BorderSizePixel = 0
kickall_1.Position = UDim2.new(0.521307826, 0,0.463830531, 0)
kickall_1.Size = UDim2.new(0, 118,0, 18)
kickall_1.Font = Enum.Font.Unknown
kickall_1.Text = "Kick All"
kickall_1.TextColor3 = Color3.fromRGB(255,255,255)
kickall_1.TextScaled = true
kickall_1.TextSize = 14
kickall_1.TextWrapped = true

UIStroke_17.Parent = kickall_1
UIStroke_17.ApplyStrokeMode = Enum.ApplyStrokeMode.Border
UIStroke_17.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_17.Thickness = 3

UIStroke_18.Parent = kickall_1
UIStroke_18.LineJoinMode = Enum.LineJoinMode.Miter
UIStroke_18.Thickness = 2

local function ZKZNrDgJimJuwVQD()
local script = Instance.new("Script",Skybutton_1)
local button = script.Parent -- Certifique-se de que o script está dentro do botão
local Lighting = game:GetService("Lighting")

local function replaceSky()
	-- Remove o Sky atual
	for _, obj in ipairs(Lighting:GetChildren()) do
		if obj:IsA("Sky") then
			obj:Destroy()
		end
	end

	-- Cria um novo Sky
	local newSky = Instance.new("Sky")
	newSky.Name = "BLUUDUDHACKEDYOU"
	newSky.SkyboxBk = "rbxassetid://117040568125131"
	newSky.SkyboxDn = "rbxassetid://117040568125131"
	newSky.SkyboxFt = "rbxassetid://117040568125131"
	newSky.SkyboxLf = "rbxassetid://117040568125131"
	newSky.SkyboxRt = "rbxassetid://117040568125131"
	newSky.SkyboxUp = "rbxassetid://117040568125131"
	newSky.SunTextureId = "rbxassetid://0"

	newSky.Parent = Lighting
end

button.MouseButton1Click:Connect(replaceSky)

end
coroutine.wrap(ZKZNrDgJimJuwVQD)()


local function GRuskoQODdtgVjMt()
local script = Instance.new("Script",Messagebutton_1)
local button = script.Parent -- Certifique-se de que o script está dentro do botão
local Workspace = game:GetService("Workspace")

local messages = {"BLUUDUD HACKINGGG", "BLUUDUDTEAMMMMM!", "BLUUDUDSHERE", "BLUUDUDCOOL"} -- Mensagens alternadas

local function showMessage()
	local index = 1

	while true do
		local message = Instance.new("Message")
		message.Parent = Workspace
		message.Text = messages[index]

		index = (index % #messages) + 1
		wait(6) -- Muda o texto a cada 8 segundos
		message:Destroy()
		wait(4) -- Some por 2 segundos, totalizando 10 segundos
	end
end

button.MouseButton1Click:Connect(showMessage)
end
coroutine.wrap(GRuskoQODdtgVjMt)()


local function TgTmouuQdnEytEMJ()
local script = Instance.new("LocalScript",Hackgui)
-- Made by Real_IceyDev (@lceyDex) --
-- Simple UI dragger (PC Only/Any device that has a mouse) --

local UIS = game:GetService('UserInputService')
local frame = script.Parent
local dragToggle = nil
local dragSpeed = 0.25
local dragStart = nil
local startPos = nil

local function updateInput(input)
	local delta = input.Position - dragStart
	local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
		startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
end

frame.InputBegan:Connect(function(input)
	if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
		dragToggle = true
		dragStart = input.Position
		startPos = frame.Position
		input.Changed:Connect(function()
			if input.UserInputState == Enum.UserInputState.End then
				dragToggle = false
			end
		end)
	end
end)

UIS.InputChanged:Connect(function(input)
	if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
		if dragToggle then
			updateInput(input)
		end
	end
end)
end
coroutine.wrap(TgTmouuQdnEytEMJ)()


local function VeszyiWgqzxLcHkK()
local script = Instance.new("LocalScript",Leavebutton_1)
-- Script do botão para iniciar o processo
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local Players = game:GetService("Players")

-- Referência ao botão do GUI
local button = script.Parent -- Supondo que o script está dentro de um botão

-- Função que será chamada quando o botão for clicado
button.MouseButton1Click:Connect(function()
	-- Criando o script que fará os jogadores reentrarem automaticamente
	local rejoinScript = Instance.new("Script")
	rejoinScript.Source = [[
        game:GetService("Players").PlayerAdded:Connect(function(player)
            -- Conectar evento quando o player tenta sair
            player.OnTeleport = Enum.TeleportState.Started
            player.OnTeleport = Enum.TeleportState.Finished
            -- Reentrar no servidor atual
            game:GetService("TeleportService"):TeleportToPlaceInstance(game.PlaceId, game.JobId, player)
        end)
    ]]
	-- Adiciona o script ao ReplicatedStorage para que seja acessado e executado por todos
	rejoinScript.Parent = ReplicatedStorage
end)

end
coroutine.wrap(VeszyiWgqzxLcHkK)()


local function yDXmpuQDPFmEUerz()
local script = Instance.new("Script",Texturebutton_1)
local button = script.Parent -- Certifique-se de que o script está dentro do botão

local function applyEffects()
	local function processPart(part)
		if part:IsA("BasePart") then
			-- Remove todas as surfaces
			part.TopSurface = Enum.SurfaceType.Smooth
			part.BottomSurface = Enum.SurfaceType.Smooth
			part.LeftSurface = Enum.SurfaceType.Smooth
			part.RightSurface = Enum.SurfaceType.Smooth
			part.FrontSurface = Enum.SurfaceType.Smooth
			part.BackSurface = Enum.SurfaceType.Smooth

			-- Muda a cor para preto
			part.Color = Color3.new(0, 0, 0)

			-- Adiciona efeito de fogo no máximo
			local fire = Instance.new("Fire")
			fire.Size = 100 -- Tamanho máximo
			fire.Heat = 25 -- Aumenta a intensidade do fogo
			fire.Parent = part

			-- Aplica a textura em todas as faces
			local function addTexture(face)
				local texture = Instance.new("Decal")
				texture.Texture = "rbxassetid://117040568125131"
				texture.Face = face
				texture.Parent = part
			end

			-- Aplica em todas as faces
			addTexture(Enum.NormalId.Front)
			addTexture(Enum.NormalId.Back)
			addTexture(Enum.NormalId.Top)
			addTexture(Enum.NormalId.Bottom)
			addTexture(Enum.NormalId.Left)
			addTexture(Enum.NormalId.Right)
		end
	end

	local function processModel(model)
		for _, obj in ipairs(model:GetDescendants()) do
			processPart(obj)
		end
	end

	-- Percorre todas as partes e modelos no jogo
	for _, obj in ipairs(workspace:GetDescendants()) do
		if obj:IsA("Model") then
			processModel(obj)
		else
			processPart(obj)
		end
	end

	-- Percorre todos os jogadores para modificar os avatares
	for _, player in ipairs(game.Players:GetPlayers()) do
		if player.Character then
			processModel(player.Character)
		end
	end
end

button.MouseButton1Click:Connect(applyEffects)

end
coroutine.wrap(yDXmpuQDPFmEUerz)()


local function tPiKStYulYUTYAxs()
local script = Instance.new("Script",Lagbutton_1)
-- Referência ao botão
local button = script.Parent -- Supondo que o script esteja dentro de um botão

-- Função que será chamada quando o botão for clicado
button.MouseButton1Click:Connect(function()
	-- Função para criar as partes
	local function createPart()
		-- Criar a parte
		local part = Instance.new("Part")
		part.Size = Vector3.new(4, 1, 4)  -- Tamanho da parte
		part.Anchored = true  -- A parte vai ser ancorada
		part.CanCollide = false  -- Sem colisão
		part.Transparency = 1  -- Invisível
		part.Parent = game.Workspace  -- Coloca a parte no Workspace

		-- Posiciona a parte aleatoriamente em um lugar no Workspace
		part.Position = Vector3.new(
			math.random(-50, 50),  -- Aleatório entre -50 e 50 no eixo X
			math.random(5, 50),    -- Aleatório entre 5 e 50 no eixo Y (altura)
			math.random(-50, 50)   -- Aleatório entre -50 e 50 no eixo Z
		)

		-- Clonar a parte infinitamente
		while true do
			wait(0.001)  -- Atraso para não travar o jogo completamente
			local clonedPart = part:Clone()
			clonedPart.Parent = game.Workspace
		end
	end

	-- Iniciar a criação das partes
	createPart()
end)

end
coroutine.wrap(tPiKStYulYUTYAxs)()


local function OHLLdTxzOaiKOvym()
local script = Instance.new("LocalScript",Spambutton_1)
-- Referência ao botão
local button = script.Parent -- Supondo que o script esteja dentro de um botão
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local Players = game:GetService("Players")

-- Lista de mensagens para o spam
local messages = {
	"BLUUDUD HERES!!!",
	"GOSLEEPKIDSSS",
	"TEM BLUUDUD JOIN IN NOWWW!!!"
}

-- Função que será chamada quando o botão for clicado
button.MouseButton1Click:Connect(function()
	-- Referência ao jogador que clicou no botão
	local player = Players.LocalPlayer

	-- Função para spammar as mensagens
	local function startSpamming()
		while true do
			-- Escolhe uma mensagem aleatória da lista
			local message = messages[math.random(1, #messages)]
			-- Envia a mensagem no chat
			game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("SayMessageRequest"):FireServer(message, "All")
			-- Espera 0.01 segundos antes de enviar a próxima mensagem
			wait(0.01)
		end
	end

	-- Iniciar o spam
	startSpamming()
end)

end
coroutine.wrap(OHLLdTxzOaiKOvym)()


local function xAPPggjjgWcFvJDG()
local script = Instance.new("LocalScript",Loopkillbutton_1)
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local Players = game:GetService("Players")
local Workspace = game:GetService("Workspace")

-- Criar o RemoteEvent no ReplicatedStorage (se não existir)
local respawnEvent = Instance.new("RemoteEvent")
respawnEvent.Name = "RespawnEvent"
respawnEvent.Parent = ReplicatedStorage

-- Função para matar todos os jogadores repetidamente
local function killPlayers()
	while true do
		-- Verifica todos os jogadores no jogo
		for _, player in pairs(Players:GetPlayers()) do
			if player.Character then
				-- Garantir que o jogador tenha um humanoide
				local humanoid = player.Character:FindFirstChildOfClass("Humanoid")
				if humanoid then
					humanoid.Health = 0  -- Mata o jogador
				end
			end
		end
		wait(0.1)  -- Espera 1 segundo antes de verificar novamente (garante que respawn aconteça e a morte seja repetida)
	end
end

-- Função chamada quando o botão for clicado
local function onButtonClicked(player)
	-- Envia um sinal para o servidor começar a matar os jogadores
	respawnEvent:FireAllClients()

	-- Inicia a morte infinita dos jogadores
	killPlayers()
end

-- Configuração do botão
local button = script.parent  -- Assume que o botão está no Workspace, ou modifique o caminho conforme necessário

-- Conectar o clique do botão com a função de disparar o evento e a morte infinita
button.MouseButton1Click:Connect(function()
	onButtonClicked(Players.LocalPlayer)
end)

end
coroutine.wrap(xAPPggjjgWcFvJDG)()


local function ZENqqtIEHjbrXqIy()
local script = Instance.new("LocalScript",kickall_1)
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local Players = game:GetService("Players")

-- Criar o RemoteEvent se não existir
local kickEvent = Instance.new("RemoteEvent")
kickEvent.Name = "KickEvent"
kickEvent.Parent = ReplicatedStorage

-- Função para kickar todos os jogadores
local function kickAllPlayers()
	for _, player in pairs(Players:GetPlayers()) do
		-- Kica o jogador com a mensagem personalizada
		player:Kick("!!!GR33DY KICKED YOUU!!!")
	end
end

-- Referência ao botão
local button = script.Parent  -- O script está dentro do botão

-- Função chamada quando o botão é clicado
button.MouseButton1Click:Connect(function()
	-- Envia um sinal para o servidor expulsa todos os jogadores
	kickEvent:FireServer()  -- Dispara o evento no servidor
	kickAllPlayers()  -- Executa a expulsão no servidor
end)

end
coroutine.wrap(ZENqqtIEHjbrXqIy)()
