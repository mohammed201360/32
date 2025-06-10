loadstring(game:HttpGet(("https://raw.githubusercontent.com/S2EXE/Shub-ui/refs/heads/main/Src")))()
MakeWindow({
  Hub = {
    Title = "مطور السكربت كرم الله",
    Animation = "مرحبا بكم.مطور السكربت كرم الله"
  },
  Key = {
    KeySystem = false,
    Title = "Key System",
    Description = "",
    KeyLink = "",
    Keys = {"1234"},
    Notifi = {
      Notifications = true,
      CorrectKey = "Running the Script...",
      Incorrectkey = "The key is incorrect",
      CopyKeyLink = "Copied to Clipboard"
    }
  }
})

--[[
  Hub = {
    Title = "shub" -- <string> عنوان السكربت
    Animation = "مرحبا" -- <string> تقدر تحط اي شيء

  Key = {
    KeySystem = <bollean> Adds a key system
    Title = "Key System" <string> Add a title to your key system
    Description = "" <string> Adds a description to your key system
    KeyLink = "" <string> Add the Link where you get the HUB key
    Keys = {"1234"} <table> Add the Keys
    Notifi = {
      Notifications = true <boolean> Add notifications to the key system
      CorrectKey = "Running the Script..." <string> notification when key is correct
      Incorrectkey = "The key is incorrect" <string> notification when key is incorrect
      CopyKeyLink = "Copied to Clipboard" <string> notification when key link is copied
    }
  }
]]
local Main = MakeTab({Name = "تفعيل السكربت"})
--[[ 
  Name = "نافذة الرئيسية" <string> اسم النافذة
]]
AddButton(Main, {
  Name = "سكربت الطيران",
  Callback = function()
    --ARCEUS X FLY V2 SCRIPT
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
  end
})

--[[
  Name = "Button Testing" <string> اسم الزر
  Callback = function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Pro69Yes/sussy-Script/main/SecuredFlyGuiv3.lua'))()
  end
]]
