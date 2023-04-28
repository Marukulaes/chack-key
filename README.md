local key = _G.Key
local check = "checkhere?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("scripthere"))()
else
game.Players.LocalPlayer:Kick("มึงไม่มี Key อันนี้เป็นตัวเทสไม่มีให้ซื้อ")
end
