getgenv().config = {
    ["Team"] = "Pirates",
    ["FPS Boost"] = true,
    ["LocalPlayer"] = {
        ["Ken Haki"] = false,
        ["Invisible"] = false,
        ["Click Delay"] = 0.35,
        ["Panic Mode"] = {
            ["Skip Player"] = false,
            ["Run"] = 4500,
            ["Max"] = 5000,
        }
    },
    ["settings"] = {
        ["White Screen"] = false,
        ["Region_Hop"] = {
            ["Enabled"] = false,
            ["Value"] = "Singapore"
        },
        ["Webhook"] = {
            ["Enabled"] = true,
            ["URL"] = {
                ["Discord"] = "https://discord.com/api/webhooks/1217846675712905389/apaStLTnuc2n6JMI0GOcySyXEf8J3TYK1tf4MZBP4nnigw6CQTvEvqCrUjErOLNYytAI",
                ["Thumbnail"] = "default"
            }
        },
        ["Chatkill"] = {
            ["Enabled"] = true,
            ["Text"] = {
                "cay ko"
            }
        },
        ["FPS Locker"] = {
            ["Enabled"] = false,
            ["Value"] = 12
        },
        ["Bounty Lock"] = {
            ["Enabled"] = false,
            ["Value"] = 30000000
        },
        ["Ignore"] = {
            ["Buddha Users"] = true,
            ["Portal Users"] = false,
            ['Some Annoying V4'] = false,
        },
        ["Stats"] = {
            ["Auto Reset Stat If Doesnt Match"] = false,
            ["Points"] = "Sword"
        },
    },
    ["Skills"] = {
        ["Melee"] = {
            ["Time"] = 3,
            ["Enabled"] = true,
            ["Z"] = {["Enabled"] = true, ["HoldTime"] = 0.2},
            ["X"] = {["Enabled"] = true, ["HoldTime"] = 0.1},
            ["C"] = {["Enabled"] = true, ["HoldTime"] = 2}
        },
        ["Fruit"] = {
            ["Time"] = 0,
            ["Enabled"] = false,
            ["Z"] = {["Enabled"] = false, ["HoldTime"] = 0},
            ["X"] = {["Enabled"] = false, ["HoldTime"] = 0},
            ["C"] = {["Enabled"] = false, ["HoldTime"] = 0},
            ["V"] = {["Enabled"] = false, ["HoldTime"] = 0},
            ["F"] = {["Enabled"] = false, ["HoldTime"] = 0}
        },
        ["Sword"] = {
            ["Time"] = 1,
            ["Enabled"] = true,
            ["Z"] = {["Enabled"] = true, ["HoldTime"] = 0.1},
            ["X"] = {["Enabled"] = true, ["HoldTime"] = 0.5},
        },
        ["Gun"] = {
            ["Time"] = 0,
            ["Enabled"] = false,
            ["GunMode"] = false,
            ["Z"] = {["Enabled"] = false, ["HoldTime"] = 0},
            ["X"] = {["Enabled"] = false, ["HoldTime"] = 0},
        }
    }
}

loadstring(game:HttpGet(("https://raw.githubusercontent.com/LeNguyenBaoPhuc/BloxFruits/main/Bounty.lua")))()
