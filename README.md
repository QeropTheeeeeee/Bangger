while task.wait() do
    local args = {
        [1] = "CashOut"
    }
    
    game:GetService("ReplicatedStorage").Signals.ActivateEssentials:FireServer(unpack(args))
    local args = {
        [1] = "Workers"
    }
    
    game:GetService("ReplicatedStorage").Signals.ActivateEssentials:FireServer(unpack(args))
    local args = {
        [1] = "Speed"
    }
    
    game:GetService("ReplicatedStorage").Signals.ActivateEssentials:FireServer(unpack(args))
local args = {
    [1] = "Strength"
}

game:GetService("ReplicatedStorage").Signals.ActivateEssentials:FireServer(unpack(args))
end
