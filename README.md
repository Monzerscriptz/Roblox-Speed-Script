local player = game.Players.LocalPlayer

local character = player.Character or player.CharacterAdded:Wait()

local humanoid = character:WaitForChild("Humanoid")

-- Set the walk speed

humanoid.WalkSpeed = 70
