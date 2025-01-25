if game.PlaceId == 6447798030 then
    loadstring(game:HttpGet('https://raw.githubusercontent.com/nick0022/funkfriday/refs/heads/main/README.md'))()
else
    local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
    Fluent:Notify({Title = "Moon Hub", Content = "Unsupported Game", Duration = 3})
end
