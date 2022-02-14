local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/PowerxCANDYYY/UI/main/README.md"))()
local venyx = library.new("MUCAS X HUB v.0.0.1 ┃ BLOX FRUITS UPDATE 17", 5013109572)

-- themes
local themes = {
Background = Color3.fromRGB(24, 24, 24),
Glow = Color3.fromRGB(0, 0, 0),
Accent = Color3.fromRGB(10, 10, 10),
LightContrast = Color3.fromRGB(20, 20, 20),
DarkContrast = Color3.fromRGB(14, 14, 14),  
TextColor = Color3.fromRGB(255, 255, 255)
}


-- first page
local page = venyx:addPage("Main", 7040391851)
local section1 = page:addSection("Auto Fram")
local section2 = page:addSection("Player")

    OldWorld = false
    newworld = false
    sea3world = false
    Test = "Magnet"
    local placeId = game.PlaceId
    if placeId == 2753915549 then
      OldWorld = true
    elseif placeId == 4442272183 then
      newworld = true
    elseif placeId == 7449423635 then
        sea3world = true
    end

section1:addToggle("Auto Fram Level", false, function(value)
    _G.AUTOFARM = value

    local Level = game.Players.LocalPlayer.Data.Level.Value
    
    while _G.AUTOFARM do wait()
    
        if OldWorld then
    if Level == 1 or Level <= 9 then
    Ms = "Bandit [Lv. 5]"
    NQ = "BanditQuest1"
    QN = 1
    QP = CFrame.new(1060.50696, 16.5166187, 1544.14075, -0.978634059, -9.24266104e-08, 0.205609754, -9.42232532e-08, 1, 1.05308562e-09, -0.205609754, -1.83426341e-08, -0.978634059)
    PUK = CFrame.new(1060.50696, 16.5166187, 1544.14075, 0.217811197, 0, -0.975990951, -0, 1, -0, 0.975990951, 0, 0.217811197)
    elseif Level == 10 or Level <= 14 then
    Ms = "Monkey [Lv. 14]"
    NQ = "JungleQuest"
    QN = 1
    QP = CFrame.new(-1600.5083, 36.8521385, 152.779541, -0.204120621, 4.53535209e-09, -0.978945732, 5.15228749e-10, 1, 4.52546312e-09, 0.978945732, 4.19359381e-10, -0.204120621)
    PUK = CFrame.new(-1767.11255, 60.8351021, 47.3190079, -0.748183727, -1.45821389e-07, 0.663491428, 3.4207627e-08, 1, 2.58352884e-07, -0.663491428, 2.15991903e-07, -0.748183727)
    elseif Level == 15 or Level <= 29 then -- Gorilla
    Ms = "Gorilla [Lv. 20]"
    NQ = "JungleQuest"
    QN = 2
    QP = CFrame.new(-1601.6553955078, 36.85213470459, 153.38809204102)
    PUK = CFrame.new(-1142.6488037109, 40.462348937988, -515.39227294922)
    elseif Level == 30 or Level <= 39 then -- Pirate
    Ms = "Pirate [Lv. 35]"
    NQ = "BuggyQuest1"
    QN = 1
    QP = CFrame.new(-1140.1761474609, 4.752049446106, 3827.4057617188)
    PUK = CFrame.new(-1201.0881347656, 40.628940582275, 3857.5966796875)
    elseif Level == 40 or Level <= 59 then -- Brute
    Ms = "Brute [Lv. 45]"
    NQ = "BuggyQuest1"
    QN = 2
    QP = CFrame.new(-1140.1761474609, 4.752049446106, 3827.4057617188)
    PUK = CFrame.new(-1387.5324707031, 24.592035293579, 4100.9575195313)
    elseif Level == 60 or Level <= 74 then -- Desert Bandit
    Ms = "Desert Bandit [Lv. 60]"
    NQ = "DesertQuest"
    QN = 1
    QP = CFrame.new(896.51721191406, 6.4384617805481, 4390.1494140625)
    PUK = CFrame.new(984.99896240234, 16.109552383423, 4417.91015625)
    elseif Level == 75 or Level <= 89 then -- Desert Officer
    Ms = "Desert Officer [Lv. 70]"
    NQ = "DesertQuest"
    QN = 2
    QP = CFrame.new(896.51721191406, 6.4384617805481, 4390.1494140625)
    PUK = CFrame.new(1547.1510009766, 14.452038764954, 4381.8002929688)
    elseif Level == 90 or Level <= 99 then -- Snow Bandit
    Ms = "Snow Bandit [Lv. 90]"
    NQ = "SnowQuest"
    QN = 1
    QP = CFrame.new(1386.8073730469, 87.272789001465, -1298.3576660156)
    PUK = CFrame.new(1356.3028564453, 105.76865386963, -1328.2418212891)
    elseif Level == 100 or Level <= 119 then -- Snowman
    Ms = "Snowman [Lv. 100]"
    NQ = "SnowQuest"
    QN = 2
    QP = CFrame.new(1386.8073730469, 87.272789001465, -1298.3576660156)
    PUK = CFrame.new(1218.7956542969, 138.01184082031, -1488.0262451172)
    elseif Level == 120 or Level <= 149 then -- Chief Petty Officer
    Ms = "Chief Petty Officer [Lv. 120]"
    NQ = "MarineQuest2"
    QN = 1
    QP = CFrame.new(-5035.49609375, 28.677835464478, 4324.1840820313)
    PUK = CFrame.new(-4931.1552734375, 65.793113708496, 4121.8393554688)
    elseif Level == 150 or Level <= 174 then -- Sky Bandit
    Ms = "Sky Bandit [Lv. 150]"
    NQ = "SkyQuest"
    QN = 1
    QP = CFrame.new(-4842.1372070313, 717.69543457031, -2623.0483398438)
    PUK = CFrame.new(-4955.6411132813, 365.46365356445, -2908.1865234375)
    elseif Level == 175 or Level <= 224 then -- Dark Master
    Ms = "Dark Master [Lv. 175]"
    NQ = "SkyQuest"
    QN = 2
    QP = CFrame.new(-4842.1372070313, 717.69543457031, -2623.0483398438)
    PUK = CFrame.new(-5148.1650390625, 439.04571533203, -2332.9611816406)
    elseif Level == 225 or Level <= 274 then -- Toga Warrior
    Ms = "Toga Warrior [Lv. 225]"
    NQ = "ColosseumQuest"
    QN = 1
    QP = CFrame.new(-1577.7890625, 7.4151420593262, -2984.4838867188)
    PUK = CFrame.new(-1872.5166015625, 49.080215454102, -2913.810546875)
    elseif Level == 275 or Level <= 299 then -- Gladiator
    Ms = "Gladiator [Lv. 275]"
    NQ = "ColosseumQuest"
    QN = 2
    QP = CFrame.new(-1577.7890625, 7.4151420593262, -2984.4838867188)
    PUK = CFrame.new(-1521.3740234375, 81.203170776367, -3066.3139648438)
    elseif Level == 300 or Level <= 329 then -- Military Soldier
    Ms = "Military Soldier [Lv. 300]"
    NQ = "MagmaQuest"
    QN = 1
    QP = CFrame.new(-5316.1157226563, 12.262831687927, 8517.00390625)
    PUK = CFrame.new(-5369.0004882813, 61.24352645874, 8556.4921875)
    elseif Level == 330 or Level <= 374 then -- Military Spy
    Ms = "Military Spy [Lv. 330]"
    NQ = "MagmaQuest"
    QN = 2
    QP = CFrame.new(-5316.1157226563, 12.262831687927, 8517.00390625)
    PUK = CFrame.new(-5984.0532226563, 82.14656829834, 8753.326171875)
    elseif Level == 375 or Level <= 399 then -- Fishman Warrior 
    Ms = "Fishman Warrior [Lv. 375]"
    NQ = "FishmanQuest"
    QN = 1
    QP = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)
    PUK = CFrame.new(60844.10546875, 98.462875366211, 1298.3985595703)
    elseif Level == 400 or Level <= 449 then -- Fishman Commando
    Ms = "Fishman Commando [Lv. 400]"
    NQ = "FishmanQuest"
    QN = 2
    QP = CFrame.new(61122.65234375, 18.497442245483, 1569.3997802734)
    PUK = CFrame.new(61738.3984375, 64.207321166992, 1433.8375244141)
    elseif Level == 450 or Level <= 474 then -- God's Guard
    Ms = "God's Guard [Lv. 450]"
    NQ = "SkyExp1Quest"
    QN = 1
    QP = CFrame.new(-4721.8603515625, 845.30297851563, -1953.8489990234)
    PUK = CFrame.new(-4628.0498046875, 866.92877197266, -1931.2352294922)
    elseif Level == 475 or Level <= 524 then -- Shanda
    Ms = "Shanda [Lv. 475]"
    NQ = "SkyExp1Quest"
    QN = 2
    QP = CFrame.new(-7863.1596679688, 5545.5190429688, -378.42266845703)
    PUK = CFrame.new(-7685.1474609375, 5601.0751953125, -441.38876342773)
    elseif Level == 525 or Level <= 549 then -- Royal Squad
    Ms = "Royal Squad [Lv. 525]"
    NQ = "SkyExp2Quest"
    QN = 1
    QP = CFrame.new(-7903.3828125, 5635.9897460938, -1410.923828125)
    PUK = CFrame.new(-7654.2514648438, 5637.1079101563, -1407.7550048828)
    elseif Level == 550 or Level <= 624 then -- Royal Soldier
    Ms = "Royal Soldier [Lv. 550]"
    NQ = "SkyExp2Quest"
    QN = 2
    QP = CFrame.new(-7903.3828125, 5635.9897460938, -1410.923828125)
    PUK = CFrame.new(-7760.4106445313, 5679.9077148438, -1884.8112792969)
    elseif Level == 625 or Level <= 649 then -- Galley Pirate
    Ms = "Galley Pirate [Lv. 625]"
    NQ = "FountainQuest"
    QN = 1
    QP = CFrame.new(5258.2788085938, 38.526931762695, 4050.044921875)
    PUK = CFrame.new(5557.1684570313, 152.32717895508, 3998.7758789063)
    elseif Level >= 650 then -- Galley Captain
    Ms = "Galley Captain [Lv. 650]"
    NQ = "FountainQuest"
    QN = 2
    QP = CFrame.new(5258.2788085938, 38.526931762695, 4050.044921875)
    PUK = CFrame.new(5677.6772460938, 92.786109924316, 4966.6323242188)	
    end
    end
    if newworld then
        if Level == 700 or Level <= 724 then -- Raider [Lv. 700]
            Ms = "Raider [Lv. 700]"
            NQ = "Area1Quest"
            QN = 1
            QP = CFrame.new(-424.080078, 73.0055847, 1836.91589, 0.253544956, -1.42165932e-08, 0.967323601, -6.00147771e-08, 1, 3.04272909e-08, -0.967323601, -6.5768397e-08, 0.253544956)
            PUK = CFrame.new(-737.026123, 39.1748352, 2392.57959, 0.272128761, 0, -0.962260842, -0, 1, -0, 0.962260842, 0, 0.272128761)
        elseif Level == 725 or Level <= 774 then -- Mercenary [Lv. 725]
            Ms = "Mercenary [Lv. 725]"
            NQ = "Area1Quest"
            QN = 2
            QP = CFrame.new(-424.080078, 73.0055847, 1836.91589, 0.253544956, -1.42165932e-08, 0.967323601, -6.00147771e-08, 1, 3.04272909e-08, -0.967323601, -6.5768397e-08, 0.253544956)
            PUK = CFrame.new(-973.731995, 95.8733215, 1836.46936, 0.999135971, 2.02326991e-08, -0.0415605344, -1.90767793e-08, 1, 2.82094952e-08, 0.0415605344, -2.73922804e-08, 0.999135971)
          elseif Level == 775 or Level <= 799 then -- Swan Pirate [Lv. 775]
            Ms = "Swan Pirate [Lv. 775]"
            NQ = "Area2Quest"
            QN = 1
            QP = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
            PUK = CFrame.new(970.369446, 142.653198, 1217.3667, 0.162079468, -4.85452638e-08, -0.986777723, 1.03357589e-08, 1, -4.74980872e-08, 0.986777723, -2.50063148e-09, 0.162079468)
          elseif Level == 800 or Level <= 874 then -- Factory Staff [Lv. 800]
            Ms = "Factory Staff [Lv. 800]"
            NQ = "Area2Quest"
            QN = 2
            QP = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
            PUK = CFrame.new(296.786499, 72.9948196, -57.1298141, -0.876037002, -5.32364979e-08, 0.482243896, -3.87658332e-08, 1, 3.99718729e-08, -0.482243896, 1.63222538e-08, -0.876037002)
          elseif Level == 875 or Level <= 899 then -- Marine Lieutenant [Lv. 875]
            Ms = "Marine Lieutenant [Lv. 875]"
            NQ = "MarineQuest3"
            QN = 1
            QP = CFrame.new(-2442.65015, 73.0511475, -3219.11523, -0.873540044, 4.2329841e-08, -0.486752301, 5.64383384e-08, 1, -1.43220786e-08, 0.486752301, -3.99823996e-08, -0.873540044)
            PUK = CFrame.new(-2913.26367, 73.0011826, -2971.64282, 0.910507619, 0, 0.413492233, 0, 1.00000012, 0, -0.413492233, 0, 0.910507619)
          elseif Level == 900 or Level <= 949 then -- Marine Captain [Lv. 900]
            Ms = "Marine Captain [Lv. 900]"
            NQ = "MarineQuest3"
            QN = 2
            QP = CFrame.new(-2442.65015, 73.0511475, -3219.11523, -0.873540044, 4.2329841e-08, -0.486752301, 5.64383384e-08, 1, -1.43220786e-08, 0.486752301, -3.99823996e-08, -0.873540044)
            PUK = CFrame.new(-1868.67688, 73.0011826, -3321.66333, -0.971402287, 1.06502087e-08, 0.237439692, 3.68856199e-08, 1, 1.06050372e-07, -0.237439692, 1.11775684e-07, -0.971402287)
          elseif Level == 950 or Level <= 974 then -- Zombie [Lv. 950]
            Ms = "Zombie [Lv. 950]"
            NQ = "ZombieQuest"
            QN = 1
            QP = CFrame.new(-5492.79395, 48.5151672, -793.710571, 0.321800292, -6.24695815e-08, 0.946807742, 4.05616092e-08, 1, 5.21931227e-08, -0.946807742, 2.16082796e-08, 0.321800292)
            PUK = CFrame.new(-5634.83838, 126.067039, -697.665039, -0.992770672, 6.77618939e-09, 0.120025545, 1.65461245e-08, 1, 8.04023372e-08, -0.120025545, 8.18070234e-08, -0.992770672)
          elseif Level == 975 or Level <= 999 then -- Vampire [Lv. 975]
            Ms = "Vampire [Lv. 975]"
            NQ = "ZombieQuest"
            QN = 2
            QP = CFrame.new(-5492.79395, 48.5151672, -793.710571, 0.321800292, -6.24695815e-08, 0.946807742, 4.05616092e-08, 1, 5.21931227e-08, -0.946807742, 2.16082796e-08, 0.321800292)
            PUK = CFrame.new(-6030.32031, 6.4377408, -1313.5564, -0.856965423, 3.9138893e-08, -0.515373945, -1.12178942e-08, 1, 9.45958547e-08, 0.515373945, 8.68467822e-08, -0.856965423)
          elseif Level == 1000 or Level <= 1049 then -- Snow Trooper [Lv. 1000] **
            Ms = "Snow Trooper [Lv. 1000]"
            NQ = "SnowMountainQuest"
            QN = 1
            QP = CFrame.new(604.964966, 401.457062, -5371.69287, 0.353063971, 1.89520435e-08, -0.935599446, -5.81846002e-08, 1, -1.70033754e-09, 0.935599446, 5.50377841e-08, 0.353063971)
            PUK = CFrame.new(535.893433, 401.457062, -5329.6958, -0.999524176, 0, 0.0308452044, 0, 1, -0, -0.0308452044, 0, -0.999524176)
          elseif Level == 1050 or Level <= 1099 then -- Winter Warrior [Lv. 1050]
            Ms = "Winter Warrior [Lv. 1050]"
            NQ = "SnowMountainQuest"
            QN = 2
            QP = CFrame.new(604.964966, 401.457062, -5371.69287, 0.353063971, 1.89520435e-08, -0.935599446, -5.81846002e-08, 1, -1.70033754e-09, 0.935599446, 5.50377841e-08, 0.353063971)
            PUK = CFrame.new(1223.7417, 454.575226, -5170.02148, 0.473996818, 2.56845354e-08, 0.880526543, -5.62456428e-08, 1, 1.10811016e-09, -0.880526543, -5.00510211e-08, 0.473996818)
          elseif Level == 1100 or Level <= 1124 then -- Lab Subordinate [Lv. 1100]
            Ms = "Lab Subordinate [Lv. 1100]"
            NQ = "IceSideQuest"
            QN = 1
            NameMon = "Lab Subordinate"
            QP = CFrame.new(-6060.10693, 15.9868021, -4904.7876, -0.411000341, -5.06538868e-07, 0.91163528, 1.26306062e-07, 1, 6.12581289e-07, -0.91163528, 3.66916197e-07, -0.411000341)
            PUK = CFrame.new(-5769.2041, 37.9288292, -4468.38721, -0.569419742, -2.49055017e-08, 0.822046936, -6.96206541e-08, 1, -1.79282633e-08, -0.822046936, -6.74401548e-08, -0.569419742)
          elseif Level == 1125 or Level <= 1174 then -- Horned Warrior [Lv. 1125]
            Ms = "Horned Warrior [Lv. 1125]"
            NQ = "IceSideQuest"
            QN = 2
            QP = CFrame.new(-6060.10693, 15.9868021, -4904.7876, -0.411000341, -5.06538868e-07, 0.91163528, 1.26306062e-07, 1, 6.12581289e-07, -0.91163528, 3.66916197e-07, -0.411000341)
            PUK = CFrame.new(-6400.85889, 24.7645149, -5818.63574, -0.964845479, 8.65926566e-08, -0.262817472, 3.98261392e-07, 1, -1.13260398e-06, 0.262817472, -1.19745812e-06, -0.964845479)
          elseif Level == 1175 or Level <= 1199 then -- Magma Ninja [Lv. 1175]
            Ms = "Magma Ninja [Lv. 1175]"
            NQ = "FireSideQuest"
            QN = 1
            QP = CFrame.new(-5431.09473, 15.9868021, -5296.53223, 0.831796765, 1.15322464e-07, -0.555080295, -1.10814341e-07, 1, 4.17010995e-08, 0.555080295, 2.68240168e-08, 0.831796765)
            PUK = CFrame.new(-5496.65576, 58.6890411, -5929.76855, -0.885073781, 0, -0.465450764, 0, 1.00000012, -0, 0.465450764, 0, -0.885073781)
          elseif Level == 1200 or Level <= 1249 then -- Lava Pirate [Lv. 1200]
            Ms = "Lava Pirate [Lv. 1200]"
            NQ = "FireSideQuest"
            QN = 2
            QP = CFrame.new(-5431.09473, 15.9868021, -5296.53223, 0.831796765, 1.15322464e-07, -0.555080295, -1.10814341e-07, 1, 4.17010995e-08, 0.555080295, 2.68240168e-08, 0.831796765)
            PUK = CFrame.new(-5169.71729, 34.1234779, -4669.73633, -0.196780294, 0, 0.98044765, 0, 1.00000012, -0, -0.98044765, 0, -0.196780294)
          elseif Level == 1250 or Level <= 1274 then -- Ship Deckhand [Lv. 1250]
            Ms = "Ship Deckhand [Lv. 1250]"
            NQ = "ShipQuest1"
            QN = 1
            QP = CFrame.new(1037.80127, 125.092171, 32911.6016, -0.244533166, -0, -0.969640911, -0, 1.00000012, -0, 0.96964103, 0, -0.244533136)
            PUK = CFrame.new(1163.80872, 138.288452, 33058.4258, -0.998580813, 5.49076979e-08, -0.0532564968, 5.57436763e-08, 1, -1.42118655e-08, 0.0532564968, -1.71604082e-08, -0.998580813)
          elseif Level == 1275 or Level <= 1299 then -- Ship Engineer [Lv. 1275]
            Ms = "Ship Engineer [Lv. 1275]"
            NQ = "ShipQuest1"
            QN = 2
            QP = CFrame.new(1037.80127, 125.092171, 32911.6016, -0.244533166, -0, -0.969640911, -0, 1.00000012, -0, 0.96964103, 0, -0.244533136)
            PUK = CFrame.new(916.666504, 44.0920448, 32917.207, -0.99746871, -4.85034697e-08, -0.0711069331, -4.8925461e-08, 1, 4.19294288e-09, 0.0711069331, 7.66126895e-09, -0.99746871)
          elseif Level == 1300 or Level <= 1324 then -- Ship Steward [Lv. 1300]
            Ms = "Ship Steward [Lv. 1300]"
            NQ = "ShipQuest2"
            QN = 1
            QP = CFrame.new(968.80957, 125.092171, 33244.125, -0.869560242, 1.51905191e-08, -0.493826836, 1.44108379e-08, 1, 5.38534195e-09, 0.493826836, -2.43357912e-09, -0.869560242)
            PUK = CFrame.new(918.743286, 129.591064, 33443.4609, -0.999792814, -1.7070947e-07, -0.020350717, -1.72559169e-07, 1, 8.91351277e-08, 0.020350717, 9.2628369e-08, -0.999792814)
          elseif Level == 1325 or Level <= 1349 then -- Ship Officer [Lv. 1325]
            Ms = "Ship Officer [Lv. 1325]"
            NQ = "ShipQuest2"
            QN = 2
            QP = CFrame.new(968.80957, 125.092171, 33244.125, -0.869560242, 1.51905191e-08, -0.493826836, 1.44108379e-08, 1, 5.38534195e-09, 0.493826836, -2.43357912e-09, -0.869560242)
            PUK = CFrame.new(786.051941, 181.474106, 33303.2969, 0.999285698, -5.32193063e-08, 0.0377905183, 5.68968588e-08, 1, -9.62386864e-08, -0.0377905183, 9.83201005e-08, 0.999285698)
          elseif Level == 1350 or Level <= 1374 then -- Arctic Warrior [Lv. 1350]
            Ms = "Arctic Warrior [Lv. 1350]"
            NQ = "FrostQuest"
            QN = 1
            QP = CFrame.new(5669.43506, 28.2117786, -6482.60107, 0.888092756, 1.02705066e-07, 0.459664226, -6.20391774e-08, 1, -1.03572376e-07, -0.459664226, 6.34646895e-08, 0.888092756)
            PUK = CFrame.new(5995.07471, 57.3188477, -6183.47314, 0.702747107, -1.53454167e-07, -0.711440146, -1.08168464e-07, 1, -3.22542007e-07, 0.711440146, 3.03620908e-07, 0.702747107)
          elseif Level == 1375 or Level <= 1424 then -- Snow Lurker [Lv. 1375]
            Ms = "Snow Lurker [Lv. 1375]"
            NQ = "FrostQuest"
            QN = 2
            QP = CFrame.new(5669.43506, 28.2117786, -6482.60107, 0.888092756, 1.02705066e-07, 0.459664226, -6.20391774e-08, 1, -1.03572376e-07, -0.459664226, 6.34646895e-08, 0.888092756)
            PUK = CFrame.new(5518.00684, 60.5559731, -6828.80518, -0.650781393, -3.64292951e-08, 0.759265184, -4.07668654e-09, 1, 4.44854642e-08, -0.759265184, 2.58550248e-08, -0.650781393)
          elseif Level == 1425 or Level <= 1449 then -- Sea Soldier [Lv. 1425]
            Ms = "Sea Soldier [Lv. 1425]"
            NQ = "ForgottenQuest"
            QN = 1
            QP = CFrame.new(-3052.99097, 236.881363, -10148.1943, -0.997911751, 4.42321983e-08, 0.064591676, 4.90968759e-08, 1, 7.37270085e-08, -0.064591676, 7.67442998e-08, -0.997911751)
            PUK = CFrame.new(-3029.78467, 66.944252, -9777.38184, -0.998552859, 1.09555076e-08, 0.0537791774, 7.79564235e-09, 1, -5.89660658e-08, -0.0537791774, -5.84614881e-08, -0.998552859)
          elseif Level >= 1450 then -- Water Fighter [Lv. 1450]
            Ms = "Water Fighter [Lv. 1450]"
            NQ = "ForgottenQuest"
            QN = 2
            QP = CFrame.new(-3052.99097, 236.881363, -10148.1943, -0.997911751, 4.42321983e-08, 0.064591676, 4.90968759e-08, 1, 7.37270085e-08, -0.064591676, 7.67442998e-08, -0.997911751)
            PUK = CFrame.new(-3262.00098, 298.699615, -10553.6943, -0.233570755, -4.57538185e-08, 0.972339869, -5.80986068e-08, 1, 3.30992194e-08, -0.972339869, -4.87605725e-08, -0.233570755)
        end
    end
    if sea3world then
        if Level == 1500 or Level <= 1524 then -- Pirate Millionaire
            Ms = "Pirate Millionaire [Lv. 1500]"
            NQ = "PiratePortQuest"
            QN = 1
            QP = CFrame.new(-289.61752319336, 43.819011688232, 5580.0903320313)
            PUK = CFrame.new(-435.68109130859, 189.69866943359, 5551.0756835938)
        elseif Level == 1525 or Level <= 1574 then -- Pistol Billoonaire
            Ms = "Pistol Billionaire [Lv. 1525]"
            NQ = "PiratePortQuest"
            QN = 2
            QP = CFrame.new(-289.61752319336, 43.819011688232, 5580.0903320313)
            PUK = CFrame.new(-236.53652954102, 217.46676635742, 6006.0883789063)
        elseif Level == 1575 or Level <= 1599 then -- Dragon Crew Warrior
            Ms = "Dragon Crew Warrior [Lv. 1575]"
            NQ = "AmazonQuest"
            QN = 1
            QP = CFrame.new(5833.1147460938, 51.60498046875, -1103.0693359375)
            PUK = CFrame.new(6301.9975585938, 104.77153015137, -1082.6075439453)
        elseif Level == 1600 or Level <= 1624 then -- Dragon Crew Archer
            Ms = "Dragon Crew Archer [Lv. 1600]"
            NQ = "AmazonQuest"
            QN = 2
            QP = CFrame.new(5833.1147460938, 51.60498046875, -1103.0693359375)
            PUK = CFrame.new(6831.1171875, 441.76708984375, 446.58615112305)
        elseif Level == 1625 or Level <= 1649 then -- Female Islander
            Ms = "Female Islander [Lv. 1625]"
            NQ = "AmazonQuest2"
            QN = 1
            QP = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)
            PUK = CFrame.new(5792.5166015625, 848.14392089844, 1084.1818847656)
        elseif Level == 1650 or Level <= 1699 then -- Giant Islander
            Ms = "Giant Islander [Lv. 1650]"
            NQ = "AmazonQuest2"
            QN = 2
            QP = CFrame.new(5446.8793945313, 601.62945556641, 749.45672607422)
            PUK = CFrame.new(5009.5068359375, 664.11071777344, -40.960144042969)
        elseif Level == 1700 or Level <= 1724 then -- Marine Commodore
            Ms = "Marine Commodore [Lv. 1700]"
            NQ = "MarineTreeIsland"
            QN = 1
            QP = CFrame.new(2179.98828125, 28.731239318848, -6740.0551757813)
            PUK = CFrame.new(2198.0063476563, 128.71075439453, -7109.5043945313)
        elseif Level == 1725 or Level <= 1774 then -- Marine Rear Admiral
            Ms = "Marine Rear Admiral [Lv. 1725]"
            NQ = "MarineTreeIsland"
            QN = 2
            QP = CFrame.new(2179.98828125, 28.731239318848, -6740.0551757813)
            PUK = CFrame.new(3294.3142089844, 385.41125488281, -7048.6342773438)
        elseif Level == 1775 or Level <= 1799 then -- Fishman Raide
            Ms = "Fishman Raider [Lv. 1775]"
            NQ = "DeepForestIsland3"
            QN = 1
            QP = CFrame.new(-10582.759765625, 331.78845214844, -8757.666015625)
            PUK = CFrame.new(-10553.268554688, 521.38439941406, -8176.9458007813)
        elseif Level == 1800 or Level <= 1824 then -- Fishman Captain
            Ms = "Fishman Captain [Lv. 1800]"
            NQ = "DeepForestIsland3"
            QN = 2
            QP = CFrame.new(-10583.099609375, 331.78845214844, -8759.4638671875)
            PUK = CFrame.new(-10789.401367188, 427.18637084961, -9131.4423828125)
        elseif Level == 1825 or Level <= 1849 then -- Forest Pirate
            Ms = "Forest Pirate [Lv. 1825]"
            NQ = "DeepForestIsland"
            QN = 1
            QP = CFrame.new(-13232.662109375, 332.40396118164, -7626.4819335938)
            PUK = CFrame.new(-13489.397460938, 400.30349731445, -7770.251953125)
        elseif Level == 1850 or Level <= 1899 then -- Mythological Pirate
            Ms = "Mythological Pirate [Lv. 1850]"
            NQ = "DeepForestIsland"
            QN = 2
            QP = CFrame.new(-13232.662109375, 332.40396118164, -7626.4819335938)
            PUK = CFrame.new(-13508.616210938, 582.46228027344, -6985.3037109375)
        elseif Level == 1900 or Level <= 1924 then -- Jungle Pirate
            Ms = "Jungle Pirate [Lv. 1900]"
            NQ = "DeepForestIsland2"
            QN = 1
            QP = CFrame.new(-12682.096679688, 390.88653564453, -9902.1240234375)
            PUK = CFrame.new(-12267.103515625, 459.75262451172, -10277.200195313)
        elseif Level == 1925 or Level <= 1974 then -- Musketeer Pirate
            Ms = "Musketeer Pirate [Lv. 1925]"
            NQ = "DeepForestIsland2"
            QN = 2
            QP = CFrame.new(-12682.096679688, 390.88653564453, -9902.1240234375)
            PUK = CFrame.new(-13291.5078125, 520.47338867188, -9904.638671875)
        elseif Level == 1925 or Level <= 1974 then -- Musketeer Pirate
            Ms = "Musketeer Pirate [Lv. 1925]"
            NQ = "DeepForestIsland2"
            QN = 2
            QP = CFrame.new(-12682.096679688, 390.88653564453, -9902.1240234375)
            PUK = CFrame.new(-13291.5078125, 520.47338867188, -9904.638671875) 
        elseif Level == 1975 or Level <= 1999 then -- Reborn Skeleton
            Ms = "Reborn Skeleton [Lv. 1975]"
            NQ = "HauntedQuest1"
            QN = 1
            QP = CFrame.new(-9481.0439453125, 142.13061523438, 5564.1069335938)
            PUK = CFrame.new(-13291.5078125, 520.47338867188, -9904.638671875) -9481.0439453125, 142.13061523438, 5564.1069335938
	elseif Level == 2000 or Level <= 2024 then -- Living Zombie
	    Ms = "Living Zombie [Lv. 2000]"
            NQ = "HauntedQuest1"
	    QN = 2 
	    QP = CFrame.new(-9480.62305, 142.130661, 5563.63477, -0.6752159, 1.62456413e-08, -0.737620115, 4.96923391e-09, 1, 1.74755748e-08, 0.737620115, 8.13437939e-09, -0.6752159)
	    PUK = CFrame.new(-10087.9238, 398.988098, 5931.33496, 0.195364684, 0, 0.980730653, -0, 1, -0, -0.980730653, 0, 0.195364684)
       elseif Level == 2020 or Level <= 2049 then -- Demonic Soul
	    Ms = "Demonic Soul [Lv. 2025]"
            NQ = "HauntedQuest2"
	    QN = 1	 
	    QP = CFrame.new(-9518.3623046875, 172.13063049316, 6076.2333984375)
	    PUK = CFrame.new(-9677.58984375, 271.1305847168, 6261.9907226563)
       elseif Level == 2050 or Level <= 2074 then -- Posessed Mummy
	    Ms = "Posessed Mummy [Lv. 2050]"
            NQ = "HauntedQuest2"
	    QN = 2	 
	    QP = CFrame.new(-9518.3623046875, 172.13063049316, 6076.2333984375)
	    PUK = CFrame.new(-9519.087890625, 69.619895935059, 6365.482421875)
         elseif Level == 2075 or Level <= 2099 then -- Posessed Mummy
	    Ms = "Peanut Scout [Lv. 2075]"
      NQ = "NutsIslandQuest"
	    QN = 1	 
	    QP = CFrame.new(-2067.3757324219, 83.22386932373, -10130.515625)
	    PUK = CFrame.new(-2104.3034667969, 38.129970550537, -10194.590820312)
         elseif Level == 2100 or Level <= 2124 then -- Posessed Mummy
	    Ms = "Peanut President [Lv. 2100]"
      NQ = "NutsIslandQuest"
	    QN = 2	 
	    QP = CFrame.new(-2067.3757324219, 83.22386932373, -10130.515625)
	    PUK = CFrame.new(-2049.1003417969, 92.41512298584, -10636.852539062)
         elseif Level == 2125 or Level <= 10000 then -- Posessed Mummy
	    Ms = "Ice Cream Chef [Lv. 2125]"
      NQ = "IceCreamIslandQuest"
	    QN = 1	 
	    QP = CFrame.new(-820.80737304688, 65.845329284668, -10966.470703125)
	    PUK = CFrame.new(-792.66931152344, 143.80419921875, -11079.135742188)
        end
end
    pcall(function()
        if game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == true then
            -- nothing
        else
    
    function TP2(P1)
        Distance = (P1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
        if Distance < 1000 then
            Speed = 400
        elseif Distance >= 1000 then
            Speed = 250
        end
        game:GetService("TweenService"):Create(
            game.Players.LocalPlayer.Character.HumanoidRootPart,
            TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
            {CFrame = P1}
        ):Play()
        Clip = true
        wait(Distance/Speed)
        Clip = false
    end
    
    TP2(QP)
    wait(1.5)
    
    
    local args = {
        [1] = "StartQuest",
        [2] = NQ,
        [3] = QN
    }
    
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    wait(1.5)
    end
    
    function bringmon()
        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
            for k,x in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                if x.Name == Ms then
                    if v.Name == Ms then
                        v.HumanoidRootPart.CFrame = x.HumanoidRootPart.CFrame
                        v.HumanoidRootPart.CanCollide = false
                        sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                    end
                end
            end
        end
    end
    for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
        if v.Name == Ms then
    v.HumanoidRootPart.Size = Vector3.new(60,60,60)
    v.HumanoidRootPart.Transparency = 1
        end
    end
    
            for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                if v.Name == Ms and v.Humanoid.Health == 0 then
                    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = PUK
                        elseif v.Name == Ms then
                        game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
                        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,25,0)
                    end
                end
    
                bringmon()
    
                    game:GetService'VirtualUser':CaptureController()
                    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                    if game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
                    else
                    local args = {
                        [1] = "Buso"
                    }
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
                    end
    end)
    end
end)
-----------------------------------------------------------------------

--------------------------------------------------------------------------------------------------
section1:addToggle("FastAttack", true, function(value)
_G.FastAttack = value
end)

spawn(function()
    game:GetService("RunService").Stepped:Connect(function()
        if _G.FastAttack == true then
            game.Players.LocalPlayer.Character.Stun.Value = 0
            game.Players.LocalPlayer.Character.Humanoid.Sit = false
            game.Players.LocalPlayer.Character.Busy.Value = false        
        end
        wait(1)
    end)
end)

local RigC = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
    local VirtualUser = game:GetService('VirtualUser')
    local kkii = require(game.ReplicatedStorage.Util.CameraShaker)
    local LocalPlayer = game.Players.LocalPlayer
    local Framework = {
        Combat = require(LocalPlayer.PlayerScripts.CombatFramework),
        Rig = require(LocalPlayer.PlayerScripts.CombatFramework.RigController)
    }
    local cd = 0.1
    function Attack()
        spawn(function()
            while wait() do
            pcall(function()
                local Controller = Framework.Combat.activeController
                if Controller and tick() >= cd then
                    cd = tick() + 0.1
                    spawn(function()
                        Controller:attack()
                    end)
                    Controller.increment = 4
                end
            end)
        end
        end)
    end
spawn(function()
game:GetService("RunService").Stepped:Connect(function()
        if _G.FastAttack == true then
            RigC.activeController.timeToNextAttack = -(math.huge^math.huge^math.huge)
            RigC.activeController.timeToNextBlock = 0
            RigC.activeController.hitboxMagnitude = 100
            RigC.activeController.attacking = false
            RigC.activeController.increment = 3
            RigC.activeController.humanoid.AutoRotate = true
            RigC.activeController.blocking = false
            Rig.activeController.focusStart = 0
            game:GetService("VirtualUser"):CaptureController()
            game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 670),workspace.CurrentCamera.CFrame)
        end
    end)
end)
spawn(function()
game:GetService("RunService").Stepped:Connect(function()
        if _G.FastAttack == true then
            RigC.activeController.timeToNextAttack = -(math.huge^math.huge^math.huge)
            RigC.activeController.hitboxMagnitude = 50
            RigC.activeController.attacking = false
            RigC.activeController.increment = 3
        end
    end)
end)
--------------
local Weaponlist = {}
local Weapon = nil

for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
    table.insert(Weaponlist,v.Name)
end

section1:addDropdown("SelectWeapon",Weaponlist, false, function(currentOption)
    Weapon = currentOption
end)

spawn(function()
while wait() do
if _G.AutoEquiped then
pcall(function()
game.Players.LocalPlayer.Character.Humanoid:EquipTool(game:GetService("Players").LocalPlayer.Backpack:FindFirstChild(Weapon))
end)
end
end
end)

section1:addButton("Refresh Weapon",false,function(a)
    Select:Clear()
		for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do  
			if v:IsA("Tool") then
				SelectWeapona:Add(v.Name)
			end
		end
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do  
			if v:IsA("Tool") then
				SelectWeapona:Add(v.Name)
			end
		end
	end)

section1:addToggle("Select", true, function(a)
_G.AutoEquiped = a
end)
----------------------------------------------auto
section2:addToggle("Auto Electric Claw", false, function(vu)
    AutoElectricClaw = vu
	if AutoElectricClaw then
		game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
	end
end)

spawn(function()
	while wait(.1) do
		if AutoElectricClaw then
			if game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 400 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
			end
			if game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 400 then
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
			end
			if (game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value <= 399) or (game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value <= 399) then
				SelectToolWeapon = "Electro"
			end
			if game.Players.LocalPlayer.Backpack:FindFirstChild("Electric Claw") or game.Players.LocalPlayer.Character:FindFirstChild("Electric Claw") then
				SelectToolWeapon = "Electric Claw"
			end
			if (game.Players.LocalPlayer.Character:FindFirstChild("Electro") and game.Players.LocalPlayer.Character:FindFirstChild("Electro").Level.Value >= 400) or (game.Players.LocalPlayer.Backpack:FindFirstChild("Electro") and game.Players.LocalPlayer.Backpack:FindFirstChild("Electro").Level.Value >= 400) then
				if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw") == "..." and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw","Start") == 4 then
					TP(CFrame.new(-12548.998046875, 332.40396118164, -7603.1865234375))
				elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw",true) == 4 then
					Auto_Farm = false
					if (CFrame.new(-10369.7725, 331.654175, -10130.3047, 0.879783928, -1.15147909e-08, 0.475373745, -1.70712194e-10, 1, 2.45385472e-08, -0.475373745, -2.16697718e-08, 0.879783928).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 4 then
						wait(1.1)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw","Start")
					else
						TP(CFrame.new(-10369.7725, 331.654175, -10130.3047, 0.879783928, -1.15147909e-08, 0.475373745, -1.70712194e-10, 1, 2.45385472e-08, -0.475373745, -2.16697718e-08, 0.879783928))
					end
				elseif _G.AutoFarm then
					Auto_Farm = true
				end
			end
		end
	end
end)
---------------------Haki
section2:addToggle("Auto Buy Haki Color",false,function(value)

    _G.buy = value

    while _G.buy do
        wait()

        local A_1 = "ColorsDealer"
        local A_2 = "1"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "2"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "3"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "4"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "5"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "6"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "7"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "8"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "9"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "10"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "11"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "12"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

        local A_1 = "ColorsDealer"
        local A_2 = "13"
        local Event = game:GetService("ReplicatedStorage").Remotes["CommF_"]
        Event:InvokeServer(A_1, A_2)

    end

end)
----------------------------------------TEST1

----------------------------TEST
section2:addToggle("AuTo Yama",false,function(vu)
_G.AutoYama = vu
end)

section2:addToggle("AuTo Factory",false,function(vu)
_G.Factory = vu
end)

section2:addToggle("AuTo Newworld",false,function(vu)
_G.Auto_Newworld = vu
end)

section2:addToggle("AuTo Bartilo",false,function(vu)
_G.AutoBartilo = vu
end)

section2:addToggle("AuTo Rengoku",false,function(vu)
_G.AutoRengoku = vu
end)

section2:addToggle("AuTo Ecto",false,function(vu)
_G.AutoEcto = vu
end)

section2:addToggle("AuTo Bone",false,function(vu)
_G.Auto_Bone = vu
end)

section2:addToggle("AuTo Third",false,function(vu)
_G.AutoThird = vu
end)

section2:addToggle("AuTo EvoRace",false,function(vu)
_G.AutoEvoRace = vu
end)

section2:addToggle("AuTo DarkDagger Hop",false,function(vu)
_G.Auto_Dark_Dagger_Hop = vu
end)

section2:addToggle("AuTo indra Hop",false,function(vu)
_G.Auto_indra_Hop = vu
end)

section2:addToggle("AuTo DonSwan Hop",false,function(vu)
_G.AutoDonSwan_Hop = vu
end)

section2:addToggle("AuTo Pole Hop",false,function(vu)
_G.Pole_Hop = vu
end)
----------------------------------------AnitAFK
section2:addToggle("Anit AFK",true,function(vu)
    local vu = game:GetService("VirtualUser")
    game:GetService("Players").LocalPlayer.Idled:connect(function()
        vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
        wait(1)
        vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
    end)
end)
---------------------------------stats
local page = venyx:addPage("Auto Stats", 7040410130 )
local section3 = page:addSection("Auto Stats")

melee = false
		section3:addToggle("Melee",false,function(Value)
			melee = Value  
		end)
		defense = false
		section3:addToggle("Defense",false,function(Value)
			defense = Value
		end)
		sword = false
		section3:addToggle("Sword",false,function(Value)
			sword = Value
		end)
		gun = false
		section3:addToggle("Gun",false,function(Value)
			gun = Value
		end)
		demonfruit = false
		section3:addToggle("Devil Fruit",false,function(Value)
			demonfruit = Value
		end)
		PointStats = 1
		section3:addSlider("Point ",1,1,10,PointStats,function(a)
			PointStats = a
		end)

--3
spawn(function()
    while wait() do
        if game.Players.localPlayer.Data.Points.Value >= PointStats then
            if melee then
                local args = {
                    [1] = "AddPoint",
                    [2] = "Melee",
                    [3] = PointStats
                }
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
            end 
            if defense then
                local args = {
                    [1] = "AddPoint",
                    [2] = "Defense",
                    [3] = PointStats
                }
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
            end 
            if sword then
                local args = {
                    [1] = "AddPoint",
                    [2] = "Sword",
                    [3] = PointStats
                }
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
            end 
            if gun then
                local args = {
                    [1] = "AddPoint",
                    [2] = "Gun",
                    [3] = PointStats
                }
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
            end 
            if demonfruit then
                local args = {
                    [1] = "AddPoint",
                    [2] = "Demon Fruit",
                    [3] = PointStats
                }
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
            end
        end
    end
end)
---------------------------------------------------------------------------------------------TELEPORT
local sun = venyx:addPage("Telepot", 7044226690)
local Stop = sun:addSection("Teleprot1")
local Tp = sun:addSection("Teleprot1")

Stop:addButton("Stop Tween", function()
    Clip = false
    TP(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
end)

if OldWorld then

    Tp:addButton("Wild Mill", function()
        TP2(CFrame.new(1042.1501464844, 16.299360275269, 1444.3442382813))
    end)

    Tp:addButton("Marine 1st", function()
        TP2(CFrame.new(-2599.6655273438, 6.9146227836609, 2062.2216796875))
    end)

    Tp:addButton("Marine 2sd", function()
        TP2(CFrame.new(-5081.3452148438, 85.221641540527, 4257.3588867188))
    end)

    Tp:addButton("Midle Town", function()
        TP2(CFrame.new(-655.97088623047, 7.878026008606, 1573.7612304688))
    end)

    Tp:addButton("Jungle", function()
        TP2(CFrame.new(-1499.9877929688, 22.877912521362, 353.87060546875))
    end)

    Tp:addButton("Pirate Village", function()
        TP2(CFrame.new(-1163.3889160156, 44.777843475342, 3842.8276367188))
    end)

    Tp:addButton("Desert", function()
        TP2(CFrame.new(954.02056884766, 6.6275520324707, 4262.611328125))
    end)

    Tp:addButton("Frozen Village", function()
        TP2(CFrame.new(1144.5270996094, 7.3292083740234, -1164.7322998047))
    end)

    Tp:addButton("Colosseum", function()
        TP2(CFrame.new(-1667.5869140625, 39.385631561279, -3135.5817871094))
    end)

    Tp:addButton("Prison", function()
        TP2(CFrame.new(4857.6982421875, 5.6780304908752, 732.75750732422))
    end)

    Tp:addButton("Mob Leader", function()
        TP2(CFrame.new(-2841.9604492188, 7.3560485839844, 5318.1040039063))
    end)

    Tp:addButton("Magma Village", function()
        TP2(CFrame.new(-5328.8740234375, 8.6164798736572, 8427.3994140625))
    end)

    Tp:addButton("UnderWater Gate", function()
        TP2(CFrame.new(3893.953125, 5.3989524841309, -1893.4851074219))
    end)

    Tp:addButton("UnderWater City", function()
        TP2(CFrame.new(61191.12109375, 18.497436523438, 1561.8873291016))
    end)

    Tp:addButton("Fountain City", function()
        TP2(CFrame.new(5244.7133789063, 38.526943206787, 4073.4987792969))
    end)

    Tp:addButton("Sky 1st", function()
        TP2(CFrame.new(-4878.0415039063, 717.71246337891, -2637.7294921875))
    end)

    Tp:addButton("Sky 2sd", function()
        TP2(CFrame.new(-7899.6157226563, 5545.6030273438, -422.21798706055))
    end)

    Tp:addButton("Sky 3th", function()
        TP2(CFrame.new(-7868.5288085938, 5638.205078125, -1482.5548095703))
    end)
    
elseif newworld then

    Tp:addButton("Dock", function()
        TP2(CFrame.new(-12.519311904907, 19.302536010742, 2827.853515625))
    end)

    Tp:addButton("Mansion", function()
        TP2(CFrame.new(-390.34829711914, 321.89730834961, 869.00506591797))
    end)

    Tp:addButton("Kingdom Of Rose", function()
        TP2(CFrame.new(-388.29895019531, 138.35575866699, 1132.1662597656))
    end)

    Tp:addButton("Cafe", function()
        TP2(CFrame.new(-379.70889282227, 73.0458984375, 304.84692382813))
    end)

    Tp:addButton("Sunflower Field", function()
        TP2(CFrame.new(-1576.7171630859, 198.61849975586, 13.725157737732))
    end)

    Tp:addButton("Jeramy Mountain", function()
        TP2(CFrame.new(1986.3519287109, 448.95678710938, 796.70239257813))
    end)

    Tp:addButton("Colossuem", function()
        TP2(CFrame.new(-1871.8974609375, 45.820514678955, 1359.6843261719))
    end)

    Tp:addButton("Factory", function()
        TP2(CFrame.new(349.53750610352, 74.446998596191, -355.62420654297))
    end)

    Tp:addButton("The Bridge", function()
        TP2(CFrame.new(-1860.6354980469, 88.384948730469, -1859.1593017578))
    end)

    Tp:addButton("Green Bit", function()
        TP2(CFrame.new(-2202.3706054688, 73.097663879395, -2819.2687988281))
    end)

    Tp:addButton("Graveyard", function()
        TP2(CFrame.new(-5617.5927734375, 492.22183227539, -778.3017578125))
    end)

    Tp:addButton("Dark Area", function()
        TP2(CFrame.new(3464.7700195313, 13.375151634216, -3368.90234375))
    end)

    Tp:addButton("Snow Mountain", function()
        TP2(CFrame.new(561.23834228516, 401.44781494141, -5297.14453125))
    end)

    Tp:addButton("Hot Island", function()
        TP2(CFrame.new(-5505.9633789063, 15.977565765381, -5366.6123046875))
    end)

    Tp:addButton("Cold Island", function()
        TP2(CFrame.new(-5924.716796875, 15.977565765381, -4996.427734375))
    end)

    Tp:addButton("Ice Castle", function()
        TP2(CFrame.new(6111.7109375, 294.41259765625, -6716.4829101563))
    end)

    Tp:addButton("Usopp's Island", function()
        TP2(CFrame.new(4760.4985351563, 8.3444719314575, 2849.2426757813))
    end)

    Tp:addButton("inscription Island", function()
        TP2(CFrame.new(-5099.01171875, 98.241539001465, 2424.4035644531))
    end)

    Tp:addButton("Forgotten Island", function()
        TP2(CFrame.new(-3051.9514160156, 238.87203979492, -10250.807617188))
    end)

    Tp:addButton("Ghost Ship", function()
        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
    end)

    Tp:addButton("Mini Sky", function()
        TP2(CFrame.new(-262.11901855469, 49325.69140625, -35272.49609375))
    end)

elseif sea3world then

	Tp:addButton("Port Town", function()
        TP2(CFrame.new(-275.21615600586, 43.755737304688, 5451.0659179688))
    end)

	Tp:addButton("Hydra Island", function()
		TP2(CFrame.new(5541.2685546875, 668.30456542969, 195.48069763184))
	end)
	
	Tp:addButton("Gaint Tree", function()
		TP2(CFrame.new(2276.0859375, 25.87850189209, -6493.03125))
	end)
	
	Tp:addButton("Zou Island", function()
		TP2(CFrame.new(-10034.40234375, 331.78845214844, -8319.6923828125))
	end)
	
	Tp:addButton("PineApple Village", function()
		TP2(CFrame.new(-11172.950195313, 331.8049621582, -10151.033203125))
	end)
	
	Tp:addButton("Mansion", function()
		TP2(CFrame.new(-12548.998046875, 332.40396118164, -7603.1865234375))
	end)

	Tp:addButton("Castle on the Sea", function()
		TP2(CFrame.new(-5498.0458984375, 313.79473876953, -2860.6022949219))
	end)

    Tp:addButton("Graveyard Island", function()
        TP2(CFrame.new(-9515.07324, 142.130615, 5537.58398))
    end)

	Tp:addButton("Raid Lab", function()
		TP2(CFrame.new(-5057.146484375, 314.54132080078, -2934.7995605469))
	end)

	Tp:addButton("Mini Sky", function()
		TP2(CFrame.new(-263.66668701172, 49325.49609375, -35260))
	end)
end

--------------------------------------------------------
local page2 = x3Slucas:addPage("Player", 7252023075)
local section99 = x3Slucas:addSection("Buy Iteam")

SelectKillWeapon = ""


Player = ""
local SelectPlayer = Players:addDropdown("Selected Player", PlayerName, function(vu)
    SelectedKillPlayer = vu
end)

section99:addButton("Refresh Player", function()
    PlayerName = {}
    SelectPlayer:Clear()
    for i,v in pairs(game.Players:GetChildren()) do
		if v.Name ~= game.Players.LocalPlayer.Name then
	        SelectPlayer:Add(v.Name)
		end
    end
end)


section99:addToggle("Spectate Player", false, function(vu)
    Spectate = vu
    repeat game:GetService("RunService").Heartbeat:wait()
        game.Workspace.Camera.CameraSubject = game.Players:FindFirstChild(SelectedKillPlayer).Character.Humanoid
    until Spectate == false
    game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
end)

section99:addToggle("Kill All Player + Hop [Defense 1 only]", _G.AutoBounty, function()
	_G.AutoBounty = vu
end)

section99:addToggle("Safe Mode", false, function(vu)
    SafeMode = vu
	TP(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)
end)


local SelectWeapon = Players:Dropdown("Select Weapon",Wapon,function(Value)
    SelectKillWeapon = Value
end)

section99:addButton("Refresh Weapon", function()
    SelectWeapon:Clear()
	for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
		if v:IsA("Tool") then
			SelectWeapon:Add(v.Name)
		end
	end
	for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
		if v:IsA("Tool") then
			SelectWeapon:Add(v.Name)
		end
	end
end)
------------------------------------------------------------------

local theme = venyx:addPage("Store",  7294901968)
local section13 = theme:addSection("Buy Iteam")
local section16 = theme:addSection("Buy Malee")

section16:addButton("Black Leg", function()
   	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyBlackLeg")
end)

section16:addButton("Electro", function()
   	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectro")
end)

section16:addButton("Fishman Karate", function()
   	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyFishmanKarate")
end)

section16:addButton("Dragon Claw", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","1")
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BlackbeardReward","DragonClaw","2")
end)

section16:addButton("Superhuman", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySuperhuman")
end)
section16:addButton("Death Step", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDeathStep")
end)
section16:addButton("Sharkman Karate", function()
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate",true)
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuySharkmanKarate")
end)
section16:addButton("Electric Claw", function()
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw",true)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyElectricClaw")
end)

section16:addButton("Dragon Talon", function()
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon",true)
	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BuyDragonTalon")
end)

section13:addButton("SkyJump ($10,000 Beli)",function()
    local args = {
        [1] = "BuyHaki",
        [2] = "Geppo"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)

section13:addButton("Buso Haki ($25,000 Beli)",function()
    local args = {
        [1] = "BuyHaki",
        [2] = "Buso"
    }

    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)

section13:addButton("Observation haki ($750,000 Beli)",function()
    local args = {
        [1] = "KenTalk",
        [2] = "Buy"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)

section13:addButton("Soru ($100,000 Beli)",function()
    local args = {
        [1] = "BuyHaki",
        [2] = "Soru"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
---------------------------------------------------------
local Mucasx = venyx:addPage("Local Player", 5012544693)
local onff = Mucasx:addSection("Open")


onff:addButton("Fruits",function()
    local args = {
        [1] = "GetFruits"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    game.Players.localPlayer.PlayerGui.Main.FruitShop.Visible = true
end)


onff:addButton("Opan Inventory",function()
local args = {
    [1] = "getInventoryWeapons"
}
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
game.Players.localPlayer.PlayerGui.Main.Inventory.Visible = true
end)

onff:addButton("Open Color Haki",function()
    game.Players.localPlayer.PlayerGui.Main.Colors.Visible = true
end)

onff:addButton("Open Title Name",function()
    local args = {
        [1] = "getTitles"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    game.Players.localPlayer.PlayerGui.Main.Titles.Visible = true
end)
------------ESP
local theme = venyx:addPage("Raid", 7044233235)
local offf = theme:addSection("Raid")

if newworld then
	offf:addButton("Teleport To Lab", function()
		TP2(CFrame.new(-6438.73535, 250.645355, -4501.50684))
	end)
elseif Three_World then
	offf:addButton("Teleport To RaidLab", function()
		TP2(CFrame.new(-5057.146484375, 314.54132080078, -2934.7995605469))
	end)
end

offf:addToggle("Kill Aura", false, function(vu)
    Killaura = vu
end)

offf:addToggle("Auto Awakenr", false, function(vu)
    AutoAwakener = vu
end)

offf:addToggle("Auto Next Island", false, function(vu)
    NextIsland = vu
end)


offf:addToggle("Auto Raid", false, function(vu)
    _G.AutoRaid = vu
end)

offf:addDropdown("Select Raid", {"Flame","Ice","Quake","Light","Dark","String","Rumble","Magma","Human: Buddha"}, function(vu)
    _G.SelectRaid = vu
end)

offf:addToggle("Auto Buy Microchip", false, function(vu)
    AutoBuychip = vu
end)

spawn(function()
	pcall(function()
		while wait() do
			if AutoBuychip then
				if not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Special Microchip") or not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Special Microchip") then
					if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("RaidsNpc", "Select", _G.SelectRaid)
					end
				end
			end
		end
	end)
end)

spawn(function()
	while wait(.1) do
		if _G.AutoRaid or RaidSuperhuman then
			pcall(function()
				if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Timer.Visible == false then
					if AutoFullySuperhuman then
						if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") and not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Special Microchip") or not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Special Microchip") then
							for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
								if not string.find(v.Name, "Fruit") then
									game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Cousin","Buy")
								end
							end
						end
					end
					if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("RaidsNpc", "Select", _G.SelectRaid)
					end
					if game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
						game:GetService("StarterGui"):SetCore("SendNotification",
							{
								Title = "Auto Raid",
								Text = "Have Some People in Raid",
								Icon = "",
								Duration = 4
							}
						)
						wait(4)
					end
					if not game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") and game.Players.LocalPlayer.Backpack:FindFirstChild("Special Microchip") or  game.Players.LocalPlayer.Character:FindFirstChild("Special Microchip")  then
						if New_World then
							fireclickdetector(game:GetService("Workspace").Map.CircleIsland.RaidSummon2.Button.Main.ClickDetector)
						elseif Three_World then
							fireclickdetector(game:GetService("Workspace").Map["Boat Castle"].RaidSummon2.Button.Main.ClickDetector)
						end
					end
				end
			end)
		end
	end
end)

spawn(function()
	pcall(function()
		while wait(.1) do
			if AutoAwakener then
				local args = {
					[1] = "Awakener",
					[2] = "Check"
				}
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
				local args = {
					[1] = "Awakener",
					[2] = "Awaken"
				}
				game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
			end
		end
	end)
end)

spawn(function()
    while wait() do
        if Killaura or _G.AutoRaid or RaidSuperhuman then
            for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
                if v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 then
                    pcall(function()
                        repeat wait(.1)
                            sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                            v.Humanoid.Health = 0
                            v.HumanoidRootPart.CanCollide = false
                            v.HumanoidRootPart.Size = Vector3.new(50,50,50)
                            v.HumanoidRootPart.Transparency = 0.8
                        until not Killaura or not _G.AutoRaid or not RaidSuperhuman or not v.Parent or v.Humanoid.Health <= 0
                    end)
                end
            end
        end
    end
end)

spawn(function()
	pcall(function()
		while game:GetService("RunService").Heartbeat:wait() do
			if NextIsland or RaidSuperhuman or _G.AutoRaid then
				if game:GetService("Players")["LocalPlayer"].PlayerGui.Main.Timer.Visible == true and game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") or game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
					if game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 5") then
						TP(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 5"].CFrame*CFrame.new(0,80,0))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 4") then
						TP(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 4"].CFrame*CFrame.new(0,80,0))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 3") then
						TP(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 3"].CFrame*CFrame.new(0,80,0))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 2") then
						TP(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 2"].CFrame*CFrame.new(0,80,0))
					elseif game:GetService("Workspace")["_WorldOrigin"].Locations:FindFirstChild("Island 1") then
						TP(game:GetService("Workspace")["_WorldOrigin"].Locations["Island 1"].CFrame*CFrame.new(0,80,0))
					end
				elseif New_World then
					TP(CFrame.new(-6438.73535, 250.645355, -4501.50684))
				elseif Three_World then
					TP(CFrame.new(-5057.146484375, 314.54132080078, -2934.7995605469))
				end
			end
		end
	end)
end)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
local theme = venyx:addPage("Setting", 6942070576)
local off = theme:addSection("OFF ON")
local colors = theme:addSection("Coler")

for theme, color in pairs(themes) do -- all in one theme changer, i know, im cool
colors:addColorPicker(theme, color, function(color3)
venyx:setTheme(theme, color3)
end)
end

off:addKeybind("Toggle Keybind", Enum.KeyCode.RightControl, function()
print("Activated Keybind")
venyx:toggle()
end, function()
print("Changed Keybind")
end)

----------------########################################################################################################################
spawn(function()
    while wait() do
        if _G.AutoYama then
            if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter","Progress") >= 30 then
                repeat wait(.1)
                    fireclickdetector(game:GetService("Workspace").Map.Waterfall.SealedKatana.Handle.ClickDetector)
                until game.Players.LocalPlayer.Backpack:FindFirstChild("Yama") or not AutoYama
            end
        end
    end
end)

Core = false
spawn(function()
	while wait() do
		if _G.Factory then
			if game.Workspace.Enemies:FindFirstChild("Core") then
				Core = true
				Auto_Farm = false
				for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
					if Core and v.Name == "Core" and v.Humanoid.Health > 0 then
						repeat game:GetService("RunService").Heartbeat:wait()
							TP(CFrame.new(402.404296875, 182.53373718262, -414.73394775391))
							EquipWeapon(SelectToolWeapon)
							require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
							game:GetService'VirtualUser':CaptureController()
							game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
						until not Core or v.Humanoid.Health <= 0  or Factory == false
					end
				end
			elseif game.ReplicatedStorage:FindFirstChild("Core") then
				Core = true
				Auto_Farm = false
				TP(CFrame.new(402.404296875, 182.53373718262, -414.73394775391))
			elseif _G.AutoFarm and SelectToolWeapon ~= "" then
				Auto_Farm = true
				Core = false
			end
		end
	end
end)

spawn(function()
    while wait(.1) do
        if _G.Auto_Newworld then
            local Lv = game.Players.LocalPlayer.Data.Level.Value
            if Lv >= 700 and Old_World then
                Auto_Farm = false
                if game.Workspace.Map.Ice.Door.CanCollide == true and game.Workspace.Map.Ice.Door.Transparency == 0 then
                    TP2(CFrame.new(4851.8720703125, 5.6514348983765, 718.47094726563))
                    wait(.5)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("DressrosaQuestProgress","Detective")
                    EquipWeapon("Key")
                    TP2(CFrame.new(1347.7124, 37.3751602, -1325.6488))
                    wait(3)
                elseif game.Workspace.Map.Ice.Door.CanCollide == false and game.Workspace.Map.Ice.Door.Transparency == 1 then
                    if game:GetService("Workspace").Enemies:FindFirstChild("Ice Admiral [Lv. 700] [Boss]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "Ice Admiral [Lv. 700] [Boss]" and v.Humanoid.Health > 0 then
                                repeat game:GetService("RunService").Heartbeat:wait()
                                    pcall(function()
                                        EquipWeapon(SelectToolWeapon)
                                        TP(v.HumanoidRootPart.CFrame * CFrame.new(0, 25, 25))
                                        v.HumanoidRootPart.CanCollide = false
                                        v.HumanoidRootPart.Size = Vector3.new(60,60,60)
                                        v.HumanoidRootPart.Transparency = .8
                                        game:GetService("VirtualUser"):CaptureController()
                                        game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 870),workspace.CurrentCamera.CFrame)
                                    end)
                                until v.Humanoid.Health <= 0 or not v.Parent
                                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
                            end
                        end
                    else
                        TP2(CFrame.new(1347.7124, 37.3751602, -1325.6488))
                    end
                else
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelDressrosa")
                end
            end
        end
    end
end)

spawn(function()
    while wait(.1) do
        if _G.AutoBartilo then
            if game.Players.LocalPlayer.Data.Level.Value >= 850 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 0 then
                if string.find(game.Players.LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Swan Pirates") and string.find(game.Players.LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "50") and game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == true then 
                    if game:GetService("Workspace").Enemies:FindFirstChild("Swan Pirate [Lv. 775]") then
                        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                            if v.Name == "Swan Pirate [Lv. 775]" then
                                pcall(function()
                                    repeat wait(.1)
                                        EquipWeapon(MiscFarmWeapon)
										game:GetService'VirtualUser':CaptureController()
										game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										TP(v.HumanoidRootPart.CFrame * CFrame.new(0,15,0))
										require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
										PosMonBartilo = v.HumanoidRootPart.CFrame
										MagnetBatilo = true
                                    until not v.Parent or v.Humanoid.Health <= 0 or AutoBartilo == false or game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false
									MagnetBatilo = false
                                end)
                            end
                        end
                    else
						MagnetBatilo = false
						TP(CFrame.new(1057.92761, 137.614319, 1242.08069))
                    end
                else
					TP2(CFrame.new(-456.28952, 73.0200958, 299.895966))
					if (Vector3.new(-456.28952, 73.0200958, 299.895966) - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 30 then
						wait(1.1)
                    	game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest","BartiloQuest",1)
					end
                end
            elseif game.Players.LocalPlayer.Data.Level.Value >= 850 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 1 then
                if QuestBartilo == nil then
				    TP2(CFrame.new(-456.28952, 73.0200958, 299.895966))
                end
                if (Vector3.new(-456.28952, 73.0200958, 299.895966) - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 30 then
                    wait(1.1)
                    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo")
                    QuestBartilo = 1
                end
				if game.Workspace.Enemies:FindFirstChild("Jeremy [Lv. 850] [Boss]") then
					for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
						if v.Name == "Jeremy [Lv. 850] [Boss]" then
							repeat wait(.1)
								sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
								require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
								EquipWeapon(MiscFarmWeapon)
								TP(v.HumanoidRootPart.CFrame * CFrame.new(0,15,6))
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
							until not v.Parent or v.Humanoid.Health <= 0 or AutoBartilo == false
						end
					end
                else
                    if QuestBartilo == 1 then
                        TP(CFrame.new(1931.5931396484, 402.67391967773, 956.52215576172))
                    end
				end
            elseif game.Players.LocalPlayer.Data.Level.Value >= 850 and game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("BartiloQuestProgress","Bartilo") == 2 then
                TP2(game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate1.CFrame)
                wait(1)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate2.CFrame
                wait(1)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate3.CFrame
                wait(1)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate4.CFrame
                wait(1)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate5.CFrame
                wait(1)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate6.CFrame
                wait(1)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate7.CFrame
                wait(1)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.Dressrosa.BartiloPlates.Plate8.CFrame
                wait(1)
            end
        end 
    end
end)

spawn(function()
	pcall(function()
		while wait(.1) do
			if _G.AutoRengoku then
				if game.Players.LocalPlayer.Backpack:FindFirstChild("Hidden Key") or game.Players.LocalPlayer.Character:FindFirstChild("Hidden Key") then
					EquipWeapon("Hidden Key")
					TP2(CFrame.new(6571.1201171875, 299.23028564453, -6967.841796875))
				elseif game.Workspace.Enemies:FindFirstChild("Snow Lurker [Lv. 1375]") or game:GetService("Workspace").Enemies:FindFirstChild("Arctic Warrior [Lv. 1350]") then
					for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
						if (v.Name == "Snow Lurker [Lv. 1375]" or v.Name == "Arctic Warrior [Lv. 1350]") and v.Humanoid.Health > 0 then
							repeat game:GetService("RunService").Heartbeat:wait()
								EquipWeapon(MiscFarmWeapon)
								PosMonRengoku = v.HumanoidRootPart.CFrame
								require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
								TP(v.HumanoidRootPart.CFrame * Farm_Mode)
								game:GetService'VirtualUser':CaptureController()
								game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								RengokuMagnet = true
							until game.Players.LocalPlayer.Backpack:FindFirstChild("Hidden Key") or AutoRengoku == false or not v.Parent or v.Humanoid.Health <= 0
							RengokuMagnet = false
						end
					end
				else
					RengokuMagnet = false
					TP(CFrame.new(5525.7045898438, 262.90060424805, -6755.1186523438))
				end
			end
		end
	end)
end)

spawn(function()
    pcall(function()
        while wait(.1) do
            if _G.AutoEcto then
                if game:GetService("Workspace").Enemies:FindFirstChild("Ship Deckhand [Lv. 1250]") or game:GetService("Workspace").Enemies:FindFirstChild("Ship Engineer [Lv. 1275]") or game:GetService("Workspace").Enemies:FindFirstChild("Ship Steward [Lv. 1300]") or game:GetService("Workspace").Enemies:FindFirstChild("Ship Officer [Lv. 1325]") then
                    for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                        if string.find(v.Name, "Ship") then
                            repeat game:GetService("RunService").Heartbeat:wait()
								EquipWeapon(MiscFarmWeapon)
                                if string.find(v.Name, "Ship") then
                                    TP(v.HumanoidRootPart.CFrame * CFrame.new(0,15,15))
									game:GetService'VirtualUser':CaptureController()
									game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
									require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
                                    PosMonEctoplas = v.HumanoidRootPart.CFrame
                                    EctoplasMagnet = true
                                else
                                    EctoplasMagnet = false
									TP(CFrame.new(904.4072265625, 181.05767822266, 33341.38671875))
                                end
                            until AutoEcto == false or not v.Parent or v.Humanoid.Health <= 0
                        end
                    end
                else
					EctoplasMagnet = false
					local Distance = (Vector3.new(904.4072265625, 181.05767822266, 33341.38671875) - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
					if Distance > 20000 then
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("requestEntrance",Vector3.new(923.21252441406, 126.9760055542, 32852.83203125))
					end
                    TP(CFrame.new(904.4072265625, 181.05767822266, 33341.38671875))
                end
            end
        end
    end)
end)

spawn(function()
	while wait(.1) do
		pcall(function()
			if _G.Auto_Bone then
				if game:GetService("Workspace").Enemies:FindFirstChild("Reborn Skeleton [Lv. 1975]") or game:GetService("Workspace").Enemies:FindFirstChild("Living Zombie [Lv. 2000]") or game:GetService("Workspace").Enemies:FindFirstChild("Domenic Soul [Lv. 2025]") or game:GetService("Workspace").Enemies:FindFirstChild("Posessed Mummy [Lv. 2050]") then
					for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
						if v.Name == "Reborn Skeleton [Lv. 1975]" or v.Name == "Living Zombie [Lv. 2000]" or v.Name == "Demonic Soul [Lv. 2025]" or v.Name == "Posessed Mummy [Lv. 2050]" then
							if v:WaitForChild("Humanoid").Health > 0 then
								repeat game:GetService("RunService").Heartbeat:wait()
									EquipWeapon(EventWeapon)
									TP(v.HumanoidRootPart.CFrame * Farm_Mode)
									v.HumanoidRootPart.CanCollide = false
									v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
									game:GetService("VirtualUser"):CaptureController()
									game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 670),workspace.CurrentCamera.CFrame)
									MainMonBone = v.HumanoidRootPart.CFrame
									BoneMagnet = true
								until Auto_Bone == false or not v.Parent or v.Humanoid.Health <= 0
							end
						end
					end
				else
					BoneMagnet = false
					TP(CFrame.new(-9501.64453, 582.052612, 6034.20117))
				end
			end
		end)
	end
end)

spawn(function()
    pcall(function()
        while wait() do
            if _G.AutoThird then
                if game:GetService("Players").LocalPlayer.Data.Level.Value >= 1500 and New_World then
                    Auto_Farm = false
                    if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ZQuestProgress","Check") == 0 then
                        TP2(CFrame.new(-1926.3221435547, 12.819851875305, 1738.3092041016))
                        if (CFrame.new(-1926.3221435547, 12.819851875305, 1738.3092041016).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 10 then
                            wait(1.1)
                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("ZQuestProgress","Begin")
                        end
                        wait(2)
                        if game:GetService("Workspace").Enemies:FindFirstChild("rip_indra [Lv. 1500] [Boss]") then
                            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                                if v.Name == "rip_indra [Lv. 1500] [Boss]" then
                                    repeat game:GetService("RunService").Heartbeat:wait()
                                        pcall(function()
                                            EquipWeapon(SelectToolWeapon)
                                            TP(v.HumanoidRootPart.CFrame * CFrame.new(0,25,25))
                                            require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
                                            game:GetService'VirtualUser':CaptureController()
                                            game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
                                            FoundIndra = true
                                            game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("TravelZou")
                                            sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                                        end)
                                    until AutoThird == false or v.Humanoid.Health <= 0 or not v.Parent
                                end
                            end
                        elseif not game:GetService("Workspace").Enemies:FindFirstChild("rip_indra [Lv. 1500] [Boss]") and (CFrame.new(-26880.93359375, 22.848554611206, 473.18951416016).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 1000 then
                            TP(CFrame.new(-26880.93359375, 22.848554611206, 473.18951416016))
                        end
                    end
                end
            end
        end
    end)
end)

spawn(function()
	while wait(.1) do
		if _G.AutoEvoRace then
			if not game:GetService("Players").LocalPlayer.Data.Race:FindFirstChild("Evolved") then
				if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","1") == 0 then
					TP(CFrame.new(-2779.83521, 72.9661407, -3574.02002, -0.730484903, 6.39014104e-08, -0.68292886, 3.59963224e-08, 1, 5.50667032e-08, 0.68292886, 1.56424669e-08, -0.730484903))
					if (Vector3.new(-2779.83521, 72.9661407, -3574.02002) - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 4 then
						wait(1.1)
						game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","2")
					end
				elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","1") == 1 then
					pcall(function()
						if not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 1") and not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flower 1") then
							TP(game.Workspace.Flower1.CFrame)
						elseif not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 2") and not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flower 2") then
							TP(game.Workspace.Flower2.CFrame)
						elseif not game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 3") and not game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flower 3") then
							if game:GetService("Workspace").Enemies:FindFirstChild("Zombie [Lv. 950]") then
								for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
									if v.Name == "Zombie [Lv. 950]" then
										repeat game:GetService("RunService").Heartbeat:wait()
											EquipWeapon(MiscFarmWeapon)
											TP(v.HumanoidRootPart.CFrame * Farm_Mode)
											v.HumanoidRootPart.CanCollide = false
											v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
											game:GetService("VirtualUser"):CaptureController()
											game:GetService("VirtualUser"):Button1Down(Vector2.new(1280, 672))
											PosMonZombie = v.HumanoidRootPart.CFrame
											EvoMagnet = true
										until game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Flower 3") or not v.Parent or v.Humanoid.Health <= 0 or AutoEvoRace == false
										EvoMagnet = false
									end
								end
							else
								EvoMagnet = false
								TP(CFrame.new(-5854.39014, 145.093857, -686.942017, 0.379233211, -1.41975844e-08, -0.925301135, -3.77265719e-10, 1, -1.5498367e-08, 0.925301135, 6.2265797e-09, 0.379233211))
							end
						end
					end)
				elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","1") == 2 then
					game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Alchemist","3")
				end
			end
		end
	end
end)



spawn(function()
	while wait(.1) do
		if _G.Auto_Dark_Dagger_Hop then
			if game:GetService("Players").LocalPlayer.Backpack:FindFirstChild("Dark Dagger") or game:GetService("Players").LocalPlayer.Character:FindFirstChild("Dark Dagger") then
				game:Shutdown()
			end
		end
	end
end)

spawn(function()
	while wait(.1) do
		if _G.Auto_indra_Hop or _G.Auto_Dark_Dagger_Hop then
			if game:GetService("ReplicatedStorage"):FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") then
				TP(CFrame.new(-5415.3920898438, 505.74133300781, -2814.0166015625))
				for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if game:GetService("Workspace").Enemies:FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") then
						if v.Name == "rip_indra True Form [Lv. 5000] [Raid Boss]" then
							if v.Humanoid.Health > 0 then
								repeat game:GetService("RunService").Heartbeat:wait()
									EquipWeapon(SelectToolWeapon)
									game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 16, 7)
									require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
									game:GetService'VirtualUser':CaptureController()
									game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								until v.Humanoid.Health <= 0 or not v.Parent
							end
						end
					else
						TP(CFrame.new(-5415.3920898438, 505.74133300781, -2814.0166015625))
					end
				end
			end
			if (_G.Auto_Dark_Dagger_Hop or _G.Auto_indra_Hop) and Three_World and not game:GetService("ReplicatedStorage"):FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") and not game:GetService("Workspace").Enemies:FindFirstChild("rip_indra True Form [Lv. 5000] [Raid Boss]") then
				if game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible == false then
					Teleport()
					--SafeMode = true
					TP(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,10000,0))
				elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible == true then
					repeat game:GetService("RunService").Heartbeat:wait()
						local X = math.random(1,1000)
						local Z = math.random(1,1000)
						local LP = game.Players.LocalPlayer.Character
						TP(CFrame.new(X,LP.HumanoidRootPart.CFrame.Y,Z))
					until game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible == false
					Teleport()
				end
			end
		end
	end
end)

spawn(function()
	while wait(.1) do
		if _G.AutoDonSwan_Hop then
			if game:GetService("ReplicatedStorage"):FindFirstChild("Don Swan [Lv. 1000] [Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Don Swan [Lv. 1000] [Boss]") then
				TP(CFrame.new(2286.2004394531, 15.177839279175, 863.8388671875))
				for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if game:GetService("Workspace").Enemies:FindFirstChild("Don Swan [Lv. 1000] [Boss]") then
						if v.Name == "Don Swan [Lv. 1000] [Boss]" then
							if v.Humanoid.Health > 0 then
								repeat game:GetService("RunService").Heartbeat:wait()
									EquipWeapon(SelectToolWeapon)
									game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 16, 7)
									require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
									game:GetService'VirtualUser':CaptureController()
									game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								until v.Humanoid.Health <= 0 or not v.Parent
							end
						end
					else
						TP(CFrame.new(2286.2004394531, 15.177839279175, 863.8388671875))
					end
				end
			end
			if _G.AutoDonSwan_Hop and New_World and not game:GetService("ReplicatedStorage"):FindFirstChild("Don Swan [Lv. 1000] [Boss]") and game:GetService("Workspace").Enemies:FindFirstChild("Don Swan [Lv. 1000] [Boss]") then
				if game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible == false then
					Teleport()
					--SafeMode = true
					TP(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,10000,0))
				elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible == true then
					repeat game:GetService("RunService").Heartbeat:wait()
						local X = math.random(1,1000)
						local Z = math.random(1,1000)
						local LP = game.Players.LocalPlayer.Character
						TP(CFrame.new(X,LP.HumanoidRootPart.CFrame.Y,Z))
					until game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible == false
					Teleport()
				end
			end
		end
	end
end)

spawn(function()
	while wait(.1) do
		if _G.Pole_Hop then
			if game:GetService("ReplicatedStorage"):FindFirstChild("Thunder God [Lv. 575] [Boss]") or game:GetService("Workspace").Enemies:FindFirstChild("Thunder God [Lv. 575] [Boss]") then
				TP(CFrame.new(-7994.984375, 5761.025390625, -2088.6479492188))
				for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
					if game:GetService("Workspace").Enemies:FindFirstChild("Thunder God [Lv. 575] [Boss]") then
						if v.Name == "Thunder God [Lv. 575] [Boss]" then
							if v.Humanoid.Health > 0 then
								repeat game:GetService("RunService").Heartbeat:wait()
									EquipWeapon(SelectToolWeapon)
									game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 16, 7)
									require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
									game:GetService'VirtualUser':CaptureController()
									game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
								until v.Humanoid.Health <= 0 or not v.Parent
							end
						end
					else
						TP(CFrame.new(-7994.984375, 5761.025390625, -2088.6479492188))
					end
				end
			end
			if _G.Pole_Hop and Old_World and not game:GetService("ReplicatedStorage"):FindFirstChild("Thunder God [Lv. 575] [Boss]") and not game:GetService("Workspace").Enemies:FindFirstChild("Thunder God [Lv. 575] [Boss]") then
				if game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible == false then
					Teleport()
					--SafeMode = true
					TP(game.Players.LocalPlayer.Character.HumanoidRootPart.Position,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,10000,0))
				elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible == true then
					repeat game:GetService("RunService").Heartbeat:wait()
						local X = math.random(1,1000)
						local Z = math.random(1,1000)
						local LP = game.Players.LocalPlayer.Character
						TP(CFrame.new(X,LP.HumanoidRootPart.CFrame.Y,Z))
					until game:GetService("Players").LocalPlayer.PlayerGui.Main.InCombat.Visible == false
					Teleport()
				end
			end
		end
	end
end)

--if game:GetService("ReplicatedStorage"):FindFirstChild("Diablo [Lv. 1750]") or game:GetService("ReplicatedStorage"):FindFirstChild("Urban [Lv. 1750]") or game:GetService("ReplicatedStorage"):FindFirstChild("Deandre [Lv. 1750]") then

spawn(function()
	pcall(function()
		while wait() do
			if EliteHunter then
				local QuestElite = string.find(game.Players.LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Diablo") or string.find(game.Players.LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Urban") or string.find(game.Players.LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text, "Deandre")
				local ReplicatedStorage = game:GetService("ReplicatedStorage");
				local Enemies = game:GetService("Workspace").Enemies
				if ReplicatedStorage:FindFirstChild("Diablo [Lv. 1750]") or Enemies:FindFirstChild("Diablo [Lv. 1750]") or ReplicatedStorage:FindFirstChild("Urban [Lv. 1750]") or Enemies:FindFirstChild("Urban [Lv. 1750]") or ReplicatedStorage:FindFirstChild("Deandre [Lv. 1750]") or Enemies:FindFirstChild("Deadre [Lv. 1750]") then
					Elite = true
					Auto_Farm = false
					if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
						TP(CFrame.new(-5418.392578125, 313.74130249023, -2824.9157714844))
						if (Vector3.new(-5418.392578125, 313.74130249023, -2824.9157714844) - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 30 then
							wait(1.1)
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter")
						end
					elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
						if game.Players.LocalPlayer.PlayerGui.Main.Quest.Container.QuestReward.Title.Text == "Reward:\n$15,000\n60,000,000 Exp." then
							for i,v in pairs(game:GetService("ReplicatedStorage"):GetChildren()) do
								if Elite and v.Name == "Diablo [Lv. 1750]" or v.Name == "Urban [Lv. 1750]" or v.Name == "Deandre [Lv. 1750]" then
									repeat game:GetService("RunService").Heartbeat:wait()
										if QuestElite then
											EquipWeapon(SelectToolWeapon)
											TP(v.HumanoidRootPart.CFrame * CFrame.new(0, 10, 4))
											require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 1000
											game:GetService'VirtualUser':CaptureController()
											game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
										else
											TP(CFrame.new(-5418.392578125, 313.74130249023, -2824.9157714844))
											if (Vector3.new(-5418.392578125, 313.74130249023, -2824.9157714844) - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= 30 then
												wait(1.5)
												game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("EliteHunter")
											end
										end
									until not Elite or v.Humanoid.Health <= 0 or not v.Parent or not EliteHunter or game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false
								end
							end
						else
							game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AbandonHunter")
						end
					end
                end
            end
        end
    end)
end)

spawn(function()
    while wait() do 
    pcall(function()
    if _G.AUTOFARM == true then
    local Xd = Instance.new("Part")
    Xd.Name = "xd"
    Xd.Parent = game.Workspace
    Xd.Anchored = true
    Xd.Transparency = 20
    Xd.Color = Color3.fromRGB(255, 155, 0)
    Xd.Size = Vector3.new(15,0.5,15)
    Xd.Material = "Neon"


    game.Workspace["xd"].CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.X,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Y - 3.92,game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.Z)

else
    if game:GetService("Workspace"):FindFirstChild("xd") then
        game:GetService("Workspace"):FindFirstChild("xd"):Destroy()
    end
end
    end)
    end
    end)


function TP(P1)
    Distance = (P1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
    if Distance < 250 then
        Speed = 600
    elseif Distance < 500 then
        Speed = 400
    elseif Distance < 1000 then
        Speed = 350
    elseif Distance >= 1000 then
        Speed = 200
    end
    game:GetService("TweenService"):Create(
        game.Players.LocalPlayer.Character.HumanoidRootPart,
        TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
        {CFrame = P1}
    ):Play()
end

function TP2(P1)
	Distance = (P1.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
	if Distance < 1000 then
		Speed = 400
	elseif Distance >= 1000 then
		Speed = 250
	end
    game:GetService("TweenService"):Create(
        game.Players.LocalPlayer.Character.HumanoidRootPart,
        TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
        {CFrame = P1}
    ):Play()
    Clip = true
    wait(Distance/Speed)
    Clip = false
end


-------------Redemm

venyx:SelectPage(venyx.pages[1], true) -- no default for more freedom
