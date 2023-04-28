local key = _G.Key
local check = "https://raw.githubusercontent.com/Marukulaes/Key-Sazx/main/README.md?key" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://raw.githubusercontent.com/Marukulaes/Sazx-Hub/main/README.md"))()
else
game.Players.LocalPlayer:Kick("มึงไม่มี Key อันนี้เป็นตัวเทสไม่มีให้ซื้อ")
end
