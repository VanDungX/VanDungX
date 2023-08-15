--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88 
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER
]=]

-- Instances: 187 | Scripts: 90 | Modules: 0
local G2L = {};

-- StarterGui.GuiByNor
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["Name"] = [[GuiByNor]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;

-- StarterGui.GuiByNor.KeyUI
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 14;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2"]["Size"] = UDim2.new(0, 443, 0, 331);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Position"] = UDim2.new(0.26456591486930847, 0, 0.10621242225170135, 0);
G2L["2"]["Visible"] = false;
G2L["2"]["Name"] = [[KeyUI]];

-- StarterGui.GuiByNor.KeyUI.EY
G2L["3"] = Instance.new("Frame", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3"]["Size"] = UDim2.new(0, 419, 0, 23);
G2L["3"]["Position"] = UDim2.new(-0.03412075340747833, 0, -0.11945392191410065, 0);
G2L["3"]["Name"] = [[EY]];

-- StarterGui.GuiByNor.KeyUI.EY.TextLabel
G2L["4"] = Instance.new("TextLabel", G2L["3"]);
G2L["4"]["TextWrapped"] = true;
G2L["4"]["TextScaled"] = true;
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4"]["TextSize"] = 14;
G2L["4"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["Size"] = UDim2.new(0, 200, 0, 23);
G2L["4"]["Text"] = [[Keyboard Gui 1.0.0]];
G2L["4"]["BackgroundTransparency"] = 1;

-- StarterGui.GuiByNor.KeyUI.EY.TextLabel
G2L["5"] = Instance.new("TextLabel", G2L["3"]);
G2L["5"]["TextWrapped"] = true;
G2L["5"]["TextScaled"] = true;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5"]["TextSize"] = 14;
G2L["5"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Size"] = UDim2.new(0, 200, 0, 23);
G2L["5"]["Text"] = [[Made By Noremius Enjoy!(Some buttons doesnt vork)]];
G2L["5"]["BackgroundTransparency"] = 1;
G2L["5"]["Position"] = UDim2.new(0.48926013708114624, 0, 0, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons
G2L["6"] = Instance.new("Frame", G2L["2"]);
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(49, 49, 49);
G2L["6"]["Size"] = UDim2.new(0, 424, 0, 301);
G2L["6"]["Position"] = UDim2.new(0.025510216131806374, 0, 0.02047784812748432, 0);
G2L["6"]["Name"] = [[Buttons]];

-- StarterGui.GuiByNor.KeyUI.Buttons.W
G2L["7"] = Instance.new("TextButton", G2L["6"]);
G2L["7"]["TextWrapped"] = true;
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["TextScaled"] = true;
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["7"]["TextSize"] = 14;
G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["7"]["Name"] = [[W]];
G2L["7"]["Text"] = [[W]];
G2L["7"]["Position"] = UDim2.new(0.12062126398086548, 0, 0.16304510831832886, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.W.LocalScript
G2L["8"] = Instance.new("LocalScript", G2L["7"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.S
G2L["9"] = Instance.new("TextButton", G2L["6"]);
G2L["9"]["TextWrapped"] = true;
G2L["9"]["BorderSizePixel"] = 0;
G2L["9"]["TextScaled"] = true;
G2L["9"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["9"]["TextSize"] = 14;
G2L["9"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["9"]["Name"] = [[S]];
G2L["9"]["Text"] = [[S]];
G2L["9"]["Position"] = UDim2.new(0.11226673424243927, 0, 0.26035594940185547, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.S.LocalScript
G2L["a"] = Instance.new("LocalScript", G2L["9"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.D
G2L["b"] = Instance.new("TextButton", G2L["6"]);
G2L["b"]["TextWrapped"] = true;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["TextScaled"] = true;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["b"]["TextSize"] = 14;
G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["b"]["Name"] = [[D]];
G2L["b"]["Text"] = [[D]];
G2L["b"]["Position"] = UDim2.new(0.22312207520008087, 0, 0.26272737979888916, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.D.LocalScript
G2L["c"] = Instance.new("LocalScript", G2L["b"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.A
G2L["d"] = Instance.new("TextButton", G2L["6"]);
G2L["d"]["TextWrapped"] = true;
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["TextScaled"] = true;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["d"]["TextSize"] = 14;
G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["d"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["d"]["Name"] = [[A]];
G2L["d"]["Text"] = [[A]];
G2L["d"]["Position"] = UDim2.new(-0.0011827386915683746, 0, 0.2629081606864929, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.A.LocalScript
G2L["e"] = Instance.new("LocalScript", G2L["d"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Q
G2L["f"] = Instance.new("TextButton", G2L["6"]);
G2L["f"]["TextWrapped"] = true;
G2L["f"]["BorderSizePixel"] = 0;
G2L["f"]["TextScaled"] = true;
G2L["f"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["f"]["TextSize"] = 14;
G2L["f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["f"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["f"]["Name"] = [[Q]];
G2L["f"]["Text"] = [[Q]];
G2L["f"]["Position"] = UDim2.new(0.010531510226428509, 0, 0.16353847086429596, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Q.LocalScript
G2L["10"] = Instance.new("LocalScript", G2L["f"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.E
G2L["11"] = Instance.new("TextButton", G2L["6"]);
G2L["11"]["TextWrapped"] = true;
G2L["11"]["BorderSizePixel"] = 0;
G2L["11"]["TextScaled"] = true;
G2L["11"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["11"]["TextSize"] = 14;
G2L["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["11"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["11"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["11"]["Name"] = [[E]];
G2L["11"]["Text"] = [[E]];
G2L["11"]["Position"] = UDim2.new(0.2216048240661621, 0, 0.16122139990329742, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.E.LocalScript
G2L["12"] = Instance.new("LocalScript", G2L["11"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.1
G2L["13"] = Instance.new("TextButton", G2L["6"]);
G2L["13"]["TextWrapped"] = true;
G2L["13"]["BorderSizePixel"] = 0;
G2L["13"]["TextScaled"] = true;
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["13"]["TextSize"] = 14;
G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["13"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["13"]["Name"] = [[1]];
G2L["13"]["Text"] = [[1]];
G2L["13"]["Position"] = UDim2.new(-0.00019235070794820786, 0, -0.00004178285598754883, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.1.LocalScript
G2L["14"] = Instance.new("LocalScript", G2L["13"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.2
G2L["15"] = Instance.new("TextButton", G2L["6"]);
G2L["15"]["TextWrapped"] = true;
G2L["15"]["BorderSizePixel"] = 0;
G2L["15"]["TextScaled"] = true;
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["15"]["TextSize"] = 14;
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["15"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["15"]["Name"] = [[2]];
G2L["15"]["Text"] = [[2]];
G2L["15"]["Position"] = UDim2.new(0.11240818351507187, 0, -0.00004178285598754883, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.2.LocalScript
G2L["16"] = Instance.new("LocalScript", G2L["15"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.3
G2L["17"] = Instance.new("TextButton", G2L["6"]);
G2L["17"]["TextWrapped"] = true;
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["TextScaled"] = true;
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["17"]["TextSize"] = 14;
G2L["17"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["17"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["17"]["Name"] = [[3]];
G2L["17"]["Text"] = [[3]];
G2L["17"]["Position"] = UDim2.new(0.22500872611999512, 0, -0.00004178285598754883, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.3.LocalScript
G2L["18"] = Instance.new("LocalScript", G2L["17"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.4
G2L["19"] = Instance.new("TextButton", G2L["6"]);
G2L["19"]["TextWrapped"] = true;
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextScaled"] = true;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["19"]["TextSize"] = 14;
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["19"]["Name"] = [[4]];
G2L["19"]["Text"] = [[4]];
G2L["19"]["Position"] = UDim2.new(0.33760926127433777, 0, -0.00004178285598754883, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.4.LocalScript
G2L["1a"] = Instance.new("LocalScript", G2L["19"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.5
G2L["1b"] = Instance.new("TextButton", G2L["6"]);
G2L["1b"]["TextWrapped"] = true;
G2L["1b"]["BorderSizePixel"] = 0;
G2L["1b"]["TextScaled"] = true;
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["1b"]["TextSize"] = 14;
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["1b"]["Name"] = [[5]];
G2L["1b"]["Text"] = [[5]];
G2L["1b"]["Position"] = UDim2.new(0.43948593735694885, 0, -0.00004178285598754883, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.5.LocalScript
G2L["1c"] = Instance.new("LocalScript", G2L["1b"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.6
G2L["1d"] = Instance.new("TextButton", G2L["6"]);
G2L["1d"]["TextWrapped"] = true;
G2L["1d"]["BorderSizePixel"] = 0;
G2L["1d"]["TextScaled"] = true;
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["1d"]["TextSize"] = 14;
G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["1d"]["Name"] = [[6]];
G2L["1d"]["Text"] = [[6]];
G2L["1d"]["Position"] = UDim2.new(0.5520864725112915, 0, -0.00004178285598754883, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.6.LocalScript
G2L["1e"] = Instance.new("LocalScript", G2L["1d"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.7
G2L["1f"] = Instance.new("TextButton", G2L["6"]);
G2L["1f"]["TextWrapped"] = true;
G2L["1f"]["BorderSizePixel"] = 0;
G2L["1f"]["TextScaled"] = true;
G2L["1f"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["1f"]["TextSize"] = 14;
G2L["1f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1f"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["1f"]["Name"] = [[7]];
G2L["1f"]["Text"] = [[7]];
G2L["1f"]["Position"] = UDim2.new(0.6646870374679565, 0, -0.00004178285598754883, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.7.LocalScript
G2L["20"] = Instance.new("LocalScript", G2L["1f"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.8
G2L["21"] = Instance.new("TextButton", G2L["6"]);
G2L["21"]["TextWrapped"] = true;
G2L["21"]["BorderSizePixel"] = 0;
G2L["21"]["TextScaled"] = true;
G2L["21"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["21"]["TextSize"] = 14;
G2L["21"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["21"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["21"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["21"]["Name"] = [[8]];
G2L["21"]["Text"] = [[8]];
G2L["21"]["Position"] = UDim2.new(0.7772876024246216, 0, -0.00004178285598754883, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.8.LocalScript
G2L["22"] = Instance.new("LocalScript", G2L["21"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.9
G2L["23"] = Instance.new("TextButton", G2L["6"]);
G2L["23"]["TextWrapped"] = true;
G2L["23"]["BorderSizePixel"] = 0;
G2L["23"]["TextScaled"] = true;
G2L["23"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["23"]["TextSize"] = 14;
G2L["23"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["23"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["23"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["23"]["Name"] = [[9]];
G2L["23"]["Text"] = [[9]];
G2L["23"]["Position"] = UDim2.new(0.8898881673812866, 0, -0.00004178285598754883, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.9.LocalScript
G2L["24"] = Instance.new("LocalScript", G2L["23"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.R
G2L["25"] = Instance.new("TextButton", G2L["6"]);
G2L["25"]["TextWrapped"] = true;
G2L["25"]["BorderSizePixel"] = 0;
G2L["25"]["TextScaled"] = true;
G2L["25"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["25"]["TextSize"] = 14;
G2L["25"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["25"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["25"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["25"]["Name"] = [[R]];
G2L["25"]["Text"] = [[R]];
G2L["25"]["Position"] = UDim2.new(0.33688631653785706, 0, 0.16122139990329742, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.R.LocalScript
G2L["26"] = Instance.new("LocalScript", G2L["25"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.T
G2L["27"] = Instance.new("TextButton", G2L["6"]);
G2L["27"]["TextWrapped"] = true;
G2L["27"]["BorderSizePixel"] = 0;
G2L["27"]["TextScaled"] = true;
G2L["27"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["27"]["TextSize"] = 14;
G2L["27"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["27"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["27"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["27"]["Name"] = [[T]];
G2L["27"]["Text"] = [[T]];
G2L["27"]["Position"] = UDim2.new(0.44144394993782043, 0, 0.16122139990329742, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.T.LocalScript
G2L["28"] = Instance.new("LocalScript", G2L["27"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Y
G2L["29"] = Instance.new("TextButton", G2L["6"]);
G2L["29"]["TextWrapped"] = true;
G2L["29"]["BorderSizePixel"] = 0;
G2L["29"]["TextScaled"] = true;
G2L["29"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["29"]["TextSize"] = 14;
G2L["29"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["29"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["29"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["29"]["Name"] = [[Y]];
G2L["29"]["Text"] = [[Y]];
G2L["29"]["Position"] = UDim2.new(0.5540444850921631, 0, 0.16122139990329742, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Y.LocalScript
G2L["2a"] = Instance.new("LocalScript", G2L["29"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.U
G2L["2b"] = Instance.new("TextButton", G2L["6"]);
G2L["2b"]["TextWrapped"] = true;
G2L["2b"]["BorderSizePixel"] = 0;
G2L["2b"]["TextScaled"] = true;
G2L["2b"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["2b"]["TextSize"] = 14;
G2L["2b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2b"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["2b"]["Name"] = [[U]];
G2L["2b"]["Text"] = [[U]];
G2L["2b"]["Position"] = UDim2.new(0.6666450500488281, 0, 0.16122139990329742, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.U.LocalScript
G2L["2c"] = Instance.new("LocalScript", G2L["2b"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.I
G2L["2d"] = Instance.new("TextButton", G2L["6"]);
G2L["2d"]["TextWrapped"] = true;
G2L["2d"]["BorderSizePixel"] = 0;
G2L["2d"]["TextScaled"] = true;
G2L["2d"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["2d"]["TextSize"] = 14;
G2L["2d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2d"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["2d"]["Name"] = [[I]];
G2L["2d"]["Text"] = [[I]];
G2L["2d"]["Position"] = UDim2.new(0.7792456150054932, 0, 0.16122139990329742, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.I.LocalScript
G2L["2e"] = Instance.new("LocalScript", G2L["2d"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.O
G2L["2f"] = Instance.new("TextButton", G2L["6"]);
G2L["2f"]["TextWrapped"] = true;
G2L["2f"]["BorderSizePixel"] = 0;
G2L["2f"]["TextScaled"] = true;
G2L["2f"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["2f"]["TextSize"] = 14;
G2L["2f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["2f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["2f"]["Size"] = UDim2.new(0, 22, 0, 33);
G2L["2f"]["Name"] = [[O]];
G2L["2f"]["Text"] = [[O]];
G2L["2f"]["Position"] = UDim2.new(0.8918461799621582, 0, 0.16122139990329742, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.O.LocalScript
G2L["30"] = Instance.new("LocalScript", G2L["2f"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.P
G2L["31"] = Instance.new("TextButton", G2L["6"]);
G2L["31"]["TextWrapped"] = true;
G2L["31"]["BorderSizePixel"] = 0;
G2L["31"]["TextScaled"] = true;
G2L["31"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["31"]["TextSize"] = 14;
G2L["31"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["31"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["31"]["Size"] = UDim2.new(0, 22, 0, 33);
G2L["31"]["Name"] = [[P]];
G2L["31"]["Text"] = [[P]];
G2L["31"]["Position"] = UDim2.new(0.950827419757843, 0, 0.16122139990329742, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.P.LocalScript
G2L["32"] = Instance.new("LocalScript", G2L["31"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F
G2L["33"] = Instance.new("TextButton", G2L["6"]);
G2L["33"]["TextWrapped"] = true;
G2L["33"]["BorderSizePixel"] = 0;
G2L["33"]["TextScaled"] = true;
G2L["33"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["33"]["TextSize"] = 14;
G2L["33"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["33"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["33"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["33"]["Name"] = [[F]];
G2L["33"]["Text"] = [[F]];
G2L["33"]["Position"] = UDim2.new(0.33304163813591003, 0, 0.25964096188545227, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F.LocalScript
G2L["34"] = Instance.new("LocalScript", G2L["33"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.G
G2L["35"] = Instance.new("TextButton", G2L["6"]);
G2L["35"]["TextWrapped"] = true;
G2L["35"]["BorderSizePixel"] = 0;
G2L["35"]["TextScaled"] = true;
G2L["35"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["35"]["TextSize"] = 14;
G2L["35"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["35"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["35"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["35"]["Name"] = [[G]];
G2L["35"]["Text"] = [[G]];
G2L["35"]["Position"] = UDim2.new(0.4456421732902527, 0, 0.25964096188545227, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.G.LocalScript
G2L["36"] = Instance.new("LocalScript", G2L["35"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.H
G2L["37"] = Instance.new("TextButton", G2L["6"]);
G2L["37"]["TextWrapped"] = true;
G2L["37"]["BorderSizePixel"] = 0;
G2L["37"]["TextScaled"] = true;
G2L["37"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["37"]["TextSize"] = 14;
G2L["37"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["37"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["37"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["37"]["Name"] = [[H]];
G2L["37"]["Text"] = [[H]];
G2L["37"]["Position"] = UDim2.new(0.558242678642273, 0, 0.25964096188545227, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.H.LocalScript
G2L["38"] = Instance.new("LocalScript", G2L["37"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.J
G2L["39"] = Instance.new("TextButton", G2L["6"]);
G2L["39"]["TextWrapped"] = true;
G2L["39"]["BorderSizePixel"] = 0;
G2L["39"]["TextScaled"] = true;
G2L["39"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["39"]["TextSize"] = 14;
G2L["39"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["39"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["39"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["39"]["Name"] = [[J]];
G2L["39"]["Text"] = [[J]];
G2L["39"]["Position"] = UDim2.new(0.670843243598938, 0, 0.25964096188545227, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.J.LocalScript
G2L["3a"] = Instance.new("LocalScript", G2L["39"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.K
G2L["3b"] = Instance.new("TextButton", G2L["6"]);
G2L["3b"]["TextWrapped"] = true;
G2L["3b"]["BorderSizePixel"] = 0;
G2L["3b"]["TextScaled"] = true;
G2L["3b"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["3b"]["TextSize"] = 14;
G2L["3b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3b"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["3b"]["Name"] = [[K]];
G2L["3b"]["Text"] = [[K]];
G2L["3b"]["Position"] = UDim2.new(0.783443808555603, 0, 0.26272737979888916, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.K.LocalScript
G2L["3c"] = Instance.new("LocalScript", G2L["3b"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.L
G2L["3d"] = Instance.new("TextButton", G2L["6"]);
G2L["3d"]["TextWrapped"] = true;
G2L["3d"]["BorderSizePixel"] = 0;
G2L["3d"]["TextScaled"] = true;
G2L["3d"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["3d"]["TextSize"] = 14;
G2L["3d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3d"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["3d"]["Name"] = [[L]];
G2L["3d"]["Text"] = [[L]];
G2L["3d"]["Position"] = UDim2.new(0.8960443735122681, 0, 0.26272737979888916, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.L.LocalScript
G2L["3e"] = Instance.new("LocalScript", G2L["3d"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Z
G2L["3f"] = Instance.new("TextButton", G2L["6"]);
G2L["3f"]["TextWrapped"] = true;
G2L["3f"]["BorderSizePixel"] = 0;
G2L["3f"]["TextScaled"] = true;
G2L["3f"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["3f"]["TextSize"] = 14;
G2L["3f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["3f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3f"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["3f"]["Name"] = [[Z]];
G2L["3f"]["Text"] = [[Z]];
G2L["3f"]["Position"] = UDim2.new(-0.0020789504051208496, 0, 0.3645792305469513, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Z.LocalScript
G2L["40"] = Instance.new("LocalScript", G2L["3f"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.X
G2L["41"] = Instance.new("TextButton", G2L["6"]);
G2L["41"]["TextWrapped"] = true;
G2L["41"]["BorderSizePixel"] = 0;
G2L["41"]["TextScaled"] = true;
G2L["41"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["41"]["TextSize"] = 14;
G2L["41"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["41"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["41"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["41"]["Name"] = [[X]];
G2L["41"]["Text"] = [[X]];
G2L["41"]["Position"] = UDim2.new(0.1105215847492218, 0, 0.3645792305469513, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.X.LocalScript
G2L["42"] = Instance.new("LocalScript", G2L["41"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.C
G2L["43"] = Instance.new("TextButton", G2L["6"]);
G2L["43"]["TextWrapped"] = true;
G2L["43"]["BorderSizePixel"] = 0;
G2L["43"]["TextScaled"] = true;
G2L["43"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["43"]["TextSize"] = 14;
G2L["43"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["43"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["43"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["43"]["Name"] = [[C]];
G2L["43"]["Text"] = [[C]];
G2L["43"]["Position"] = UDim2.new(0.22312211990356445, 0, 0.3614928126335144, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.C.LocalScript
G2L["44"] = Instance.new("LocalScript", G2L["43"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.V
G2L["45"] = Instance.new("TextButton", G2L["6"]);
G2L["45"]["TextWrapped"] = true;
G2L["45"]["BorderSizePixel"] = 0;
G2L["45"]["TextScaled"] = true;
G2L["45"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["45"]["TextSize"] = 14;
G2L["45"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["45"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["45"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["45"]["Name"] = [[V]];
G2L["45"]["Text"] = [[V]];
G2L["45"]["Position"] = UDim2.new(0.3357226550579071, 0, 0.3614928126335144, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.V.LocalScript
G2L["46"] = Instance.new("LocalScript", G2L["45"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.B
G2L["47"] = Instance.new("TextButton", G2L["6"]);
G2L["47"]["TextWrapped"] = true;
G2L["47"]["BorderSizePixel"] = 0;
G2L["47"]["TextScaled"] = true;
G2L["47"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["47"]["TextSize"] = 14;
G2L["47"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["47"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["47"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["47"]["Name"] = [[B]];
G2L["47"]["Text"] = [[B]];
G2L["47"]["Position"] = UDim2.new(0.44832319021224976, 0, 0.3645792305469513, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.B.LocalScript
G2L["48"] = Instance.new("LocalScript", G2L["47"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.N
G2L["49"] = Instance.new("TextButton", G2L["6"]);
G2L["49"]["TextWrapped"] = true;
G2L["49"]["BorderSizePixel"] = 0;
G2L["49"]["TextScaled"] = true;
G2L["49"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["49"]["TextSize"] = 14;
G2L["49"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["49"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["49"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["49"]["Name"] = [[N]];
G2L["49"]["Text"] = [[N]];
G2L["49"]["Position"] = UDim2.new(0.56092369556427, 0, 0.3645792305469513, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.N.LocalScript
G2L["4a"] = Instance.new("LocalScript", G2L["49"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.M
G2L["4b"] = Instance.new("TextButton", G2L["6"]);
G2L["4b"]["TextWrapped"] = true;
G2L["4b"]["BorderSizePixel"] = 0;
G2L["4b"]["TextScaled"] = true;
G2L["4b"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["4b"]["TextSize"] = 14;
G2L["4b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4b"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["4b"]["Name"] = [[M]];
G2L["4b"]["Text"] = [[M]];
G2L["4b"]["Position"] = UDim2.new(0.6735242605209351, 0, 0.3614928126335144, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.M.LocalScript
G2L["4c"] = Instance.new("LocalScript", G2L["4b"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Shift
G2L["4d"] = Instance.new("TextButton", G2L["6"]);
G2L["4d"]["TextWrapped"] = true;
G2L["4d"]["BorderSizePixel"] = 0;
G2L["4d"]["TextScaled"] = true;
G2L["4d"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["4d"]["TextSize"] = 14;
G2L["4d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4d"]["Size"] = UDim2.new(0, 83, 0, 33);
G2L["4d"]["Name"] = [[Shift]];
G2L["4d"]["Text"] = [[RightShift]];
G2L["4d"]["Position"] = UDim2.new(-0.002078958787024021, 0, 0.5559372901916504, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Shift.LocalScript
G2L["4e"] = Instance.new("LocalScript", G2L["4d"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Tab
G2L["4f"] = Instance.new("TextButton", G2L["6"]);
G2L["4f"]["TextWrapped"] = true;
G2L["4f"]["BorderSizePixel"] = 0;
G2L["4f"]["TextScaled"] = true;
G2L["4f"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["4f"]["TextSize"] = 14;
G2L["4f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["4f"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["4f"]["Name"] = [[Tab]];
G2L["4f"]["Text"] = [[Tab]];
G2L["4f"]["Position"] = UDim2.new(0.008644902147352695, 0, 0.4756903648376465, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Tab.LocalScript
G2L["50"] = Instance.new("LocalScript", G2L["4f"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Ctrl
G2L["51"] = Instance.new("TextButton", G2L["6"]);
G2L["51"]["TextWrapped"] = true;
G2L["51"]["BorderSizePixel"] = 0;
G2L["51"]["TextScaled"] = true;
G2L["51"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["51"]["TextSize"] = 14;
G2L["51"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["51"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["51"]["Size"] = UDim2.new(0, 83, 0, 33);
G2L["51"]["Name"] = [[Ctrl]];
G2L["51"]["Text"] = [[Ctrl]];
G2L["51"]["Position"] = UDim2.new(-0.0020789597183465958, 0, 0.672126054763794, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Ctrl.LocalScript
G2L["52"] = Instance.new("LocalScript", G2L["51"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Space
G2L["53"] = Instance.new("TextButton", G2L["6"]);
G2L["53"]["TextWrapped"] = true;
G2L["53"]["BorderSizePixel"] = 0;
G2L["53"]["TextScaled"] = true;
G2L["53"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["53"]["TextSize"] = 14;
G2L["53"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["53"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["53"]["Size"] = UDim2.new(0, 143, 0, 33);
G2L["53"]["Name"] = [[Space]];
G2L["53"]["Text"] = [[Space]];
G2L["53"]["Position"] = UDim2.new(0.2794223725795746, 0, 0.8871797919273376, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Space.LocalScript
G2L["54"] = Instance.new("LocalScript", G2L["53"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.LeftAlt
G2L["55"] = Instance.new("TextButton", G2L["6"]);
G2L["55"]["TextWrapped"] = true;
G2L["55"]["BorderSizePixel"] = 0;
G2L["55"]["TextScaled"] = true;
G2L["55"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["55"]["TextSize"] = 14;
G2L["55"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["55"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["55"]["Size"] = UDim2.new(0, 82, 0, 31);
G2L["55"]["Name"] = [[LeftAlt]];
G2L["55"]["Text"] = [[Alt]];
G2L["55"]["Position"] = UDim2.new(-0.002078958787024021, 0, 0.8871797919273376, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.LeftAlt.LocalScript
G2L["56"] = Instance.new("LocalScript", G2L["55"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Enter
G2L["57"] = Instance.new("TextButton", G2L["6"]);
G2L["57"]["TextWrapped"] = true;
G2L["57"]["BorderSizePixel"] = 0;
G2L["57"]["TextScaled"] = true;
G2L["57"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["57"]["TextSize"] = 14;
G2L["57"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["57"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["57"]["Size"] = UDim2.new(0, 83, 0, 78);
G2L["57"]["Name"] = [[Enter]];
G2L["57"]["Text"] = [[Enter]];
G2L["57"]["Position"] = UDim2.new(0.7861248254776001, 0, 0.507251501083374, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Enter.LocalScript
G2L["58"] = Instance.new("LocalScript", G2L["57"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F1
G2L["59"] = Instance.new("TextButton", G2L["6"]);
G2L["59"]["TextWrapped"] = true;
G2L["59"]["BorderSizePixel"] = 0;
G2L["59"]["TextScaled"] = true;
G2L["59"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["59"]["TextSize"] = 14;
G2L["59"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["59"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["59"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["59"]["Name"] = [[F1]];
G2L["59"]["Text"] = [[F1]];
G2L["59"]["Position"] = UDim2.new(0.22312211990356445, 0, 0.6183626651763916, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F1.LocalScript
G2L["5a"] = Instance.new("LocalScript", G2L["59"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F2
G2L["5b"] = Instance.new("TextButton", G2L["6"]);
G2L["5b"]["TextWrapped"] = true;
G2L["5b"]["BorderSizePixel"] = 0;
G2L["5b"]["TextScaled"] = true;
G2L["5b"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["5b"]["TextSize"] = 14;
G2L["5b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5b"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["5b"]["Name"] = [[F2]];
G2L["5b"]["Text"] = [[F2]];
G2L["5b"]["Position"] = UDim2.new(0.3330416679382324, 0, 0.627198338508606, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F2.LocalScript
G2L["5c"] = Instance.new("LocalScript", G2L["5b"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F3
G2L["5d"] = Instance.new("TextButton", G2L["6"]);
G2L["5d"]["TextWrapped"] = true;
G2L["5d"]["BorderSizePixel"] = 0;
G2L["5d"]["TextScaled"] = true;
G2L["5d"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["5d"]["TextSize"] = 14;
G2L["5d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5d"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["5d"]["Name"] = [[F3]];
G2L["5d"]["Text"] = [[F3]];
G2L["5d"]["Position"] = UDim2.new(0.4456422030925751, 0, 0.627198338508606, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F3.LocalScript
G2L["5e"] = Instance.new("LocalScript", G2L["5d"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F4
G2L["5f"] = Instance.new("TextButton", G2L["6"]);
G2L["5f"]["TextWrapped"] = true;
G2L["5f"]["BorderSizePixel"] = 0;
G2L["5f"]["TextScaled"] = true;
G2L["5f"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["5f"]["TextSize"] = 14;
G2L["5f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5f"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["5f"]["Name"] = [[F4]];
G2L["5f"]["Text"] = [[F4]];
G2L["5f"]["Position"] = UDim2.new(0.56092369556427, 0, 0.627198338508606, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F4.LocalScript
G2L["60"] = Instance.new("LocalScript", G2L["5f"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F5
G2L["61"] = Instance.new("TextButton", G2L["6"]);
G2L["61"]["TextWrapped"] = true;
G2L["61"]["BorderSizePixel"] = 0;
G2L["61"]["TextScaled"] = true;
G2L["61"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["61"]["TextSize"] = 14;
G2L["61"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["61"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["61"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["61"]["Name"] = [[F5]];
G2L["61"]["Text"] = [[F5]];
G2L["61"]["Position"] = UDim2.new(0.6735242605209351, 0, 0.627198338508606, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F5.LocalScript
G2L["62"] = Instance.new("LocalScript", G2L["61"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F6
G2L["63"] = Instance.new("TextButton", G2L["6"]);
G2L["63"]["TextWrapped"] = true;
G2L["63"]["BorderSizePixel"] = 0;
G2L["63"]["TextScaled"] = true;
G2L["63"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["63"]["TextSize"] = 14;
G2L["63"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["63"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["63"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["63"]["Name"] = [[F6]];
G2L["63"]["Text"] = [[F6]];
G2L["63"]["Position"] = UDim2.new(0.22312211990356445, 0, 0.6988829374313354, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F6.LocalScript
G2L["64"] = Instance.new("LocalScript", G2L["63"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F7
G2L["65"] = Instance.new("TextButton", G2L["6"]);
G2L["65"]["TextWrapped"] = true;
G2L["65"]["BorderSizePixel"] = 0;
G2L["65"]["TextScaled"] = true;
G2L["65"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["65"]["TextSize"] = 14;
G2L["65"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["65"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["65"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["65"]["Name"] = [[F7]];
G2L["65"]["Text"] = [[F7]];
G2L["65"]["Position"] = UDim2.new(0.3357226550579071, 0, 0.6952987313270569, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F7.LocalScript
G2L["66"] = Instance.new("LocalScript", G2L["65"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F8
G2L["67"] = Instance.new("TextButton", G2L["6"]);
G2L["67"]["TextWrapped"] = true;
G2L["67"]["BorderSizePixel"] = 0;
G2L["67"]["TextScaled"] = true;
G2L["67"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["67"]["TextSize"] = 14;
G2L["67"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["67"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["67"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["67"]["Name"] = [[F8]];
G2L["67"]["Text"] = [[F8]];
G2L["67"]["Position"] = UDim2.new(0.44832319021224976, 0, 0.6952987313270569, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F8.LocalScript
G2L["68"] = Instance.new("LocalScript", G2L["67"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F9
G2L["69"] = Instance.new("TextButton", G2L["6"]);
G2L["69"]["TextWrapped"] = true;
G2L["69"]["BorderSizePixel"] = 0;
G2L["69"]["TextScaled"] = true;
G2L["69"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["69"]["TextSize"] = 14;
G2L["69"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["69"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["69"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["69"]["Name"] = [[F9]];
G2L["69"]["Text"] = [[F9]];
G2L["69"]["Position"] = UDim2.new(0.56092369556427, 0, 0.6917145252227783, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F9.LocalScript
G2L["6a"] = Instance.new("LocalScript", G2L["69"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F10
G2L["6b"] = Instance.new("TextButton", G2L["6"]);
G2L["6b"]["TextWrapped"] = true;
G2L["6b"]["BorderSizePixel"] = 0;
G2L["6b"]["TextScaled"] = true;
G2L["6b"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["6b"]["TextSize"] = 14;
G2L["6b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6b"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["6b"]["Name"] = [[F10]];
G2L["6b"]["Text"] = [[F10]];
G2L["6b"]["Position"] = UDim2.new(0.6735242605209351, 0, 0.6917145252227783, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F10.LocalScript
G2L["6c"] = Instance.new("LocalScript", G2L["6b"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F11
G2L["6d"] = Instance.new("TextButton", G2L["6"]);
G2L["6d"]["TextWrapped"] = true;
G2L["6d"]["BorderSizePixel"] = 0;
G2L["6d"]["TextScaled"] = true;
G2L["6d"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["6d"]["TextSize"] = 14;
G2L["6d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6d"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["6d"]["Name"] = [[F11]];
G2L["6d"]["Text"] = [[F11]];
G2L["6d"]["Position"] = UDim2.new(0.23116502165794373, 0, 0.7633991241455078, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F11.LocalScript
G2L["6e"] = Instance.new("LocalScript", G2L["6d"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.F12
G2L["6f"] = Instance.new("TextButton", G2L["6"]);
G2L["6f"]["TextWrapped"] = true;
G2L["6f"]["BorderSizePixel"] = 0;
G2L["6f"]["TextScaled"] = true;
G2L["6f"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["6f"]["TextSize"] = 14;
G2L["6f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["6f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["6f"]["Size"] = UDim2.new(0, 42, 0, 20);
G2L["6f"]["Name"] = [[F12]];
G2L["6f"]["Text"] = [[F12]];
G2L["6f"]["Position"] = UDim2.new(0.3437655568122864, 0, 0.7633991241455078, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.F12.LocalScript
G2L["70"] = Instance.new("LocalScript", G2L["6f"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.;
G2L["71"] = Instance.new("TextButton", G2L["6"]);
G2L["71"]["TextWrapped"] = true;
G2L["71"]["BorderSizePixel"] = 0;
G2L["71"]["TextScaled"] = true;
G2L["71"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["71"]["TextSize"] = 14;
G2L["71"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["71"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["71"]["Size"] = UDim2.new(0, 42, 0, 33);
G2L["71"]["Name"] = [[;]];
G2L["71"]["Text"] = [[;]];
G2L["71"]["Position"] = UDim2.new(0.7780818939208984, 0, 0.3614928126335144, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.;.LocalScript
G2L["72"] = Instance.new("LocalScript", G2L["71"]);


-- StarterGui.GuiByNor.KeyUI.Buttons..
G2L["73"] = Instance.new("TextButton", G2L["6"]);
G2L["73"]["TextWrapped"] = true;
G2L["73"]["BorderSizePixel"] = 0;
G2L["73"]["TextScaled"] = true;
G2L["73"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["73"]["TextSize"] = 14;
G2L["73"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["73"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["73"]["Size"] = UDim2.new(0, 20, 0, 33);
G2L["73"]["Name"] = [[.]];
G2L["73"]["Text"] = [[.]];
G2L["73"]["Position"] = UDim2.new(0.8960443735122681, 0, 0.3614928126335144, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons...LocalScript
G2L["74"] = Instance.new("LocalScript", G2L["73"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.,
G2L["75"] = Instance.new("TextButton", G2L["6"]);
G2L["75"]["TextWrapped"] = true;
G2L["75"]["BorderSizePixel"] = 0;
G2L["75"]["TextScaled"] = true;
G2L["75"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["75"]["TextSize"] = 14;
G2L["75"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["75"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["75"]["Size"] = UDim2.new(0, 38, 0, 19);
G2L["75"]["Name"] = [[,]];
G2L["75"]["Text"] = [[,]];
G2L["75"]["Position"] = UDim2.new(0.12240919470787048, 0, 0.486794650554657, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.,.LocalScript
G2L["76"] = Instance.new("LocalScript", G2L["75"]);


-- StarterGui.GuiByNor.KeyUI.Buttons./
G2L["77"] = Instance.new("TextButton", G2L["6"]);
G2L["77"]["TextWrapped"] = true;
G2L["77"]["BorderSizePixel"] = 0;
G2L["77"]["TextScaled"] = true;
G2L["77"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["77"]["TextSize"] = 14;
G2L["77"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["77"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["77"]["Size"] = UDim2.new(0, 42, 0, 13);
G2L["77"]["Name"] = [[/]];
G2L["77"]["Text"] = [[/]];
G2L["77"]["Position"] = UDim2.new(0.008644902147352695, 0, 0.11577395349740982, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons./.LocalScript
G2L["78"] = Instance.new("LocalScript", G2L["77"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.+
G2L["79"] = Instance.new("TextButton", G2L["6"]);
G2L["79"]["TextWrapped"] = true;
G2L["79"]["BorderSizePixel"] = 0;
G2L["79"]["TextScaled"] = true;
G2L["79"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["79"]["TextSize"] = 14;
G2L["79"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["79"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["79"]["Size"] = UDim2.new(0, 42, 0, 13);
G2L["79"]["Name"] = [[+]];
G2L["79"]["Text"] = [[+]];
G2L["79"]["Position"] = UDim2.new(0.10515964776277542, 0, 0.11577395349740982, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.+.LocalScript
G2L["7a"] = Instance.new("LocalScript", G2L["79"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.-
G2L["7b"] = Instance.new("TextButton", G2L["6"]);
G2L["7b"]["TextWrapped"] = true;
G2L["7b"]["BorderSizePixel"] = 0;
G2L["7b"]["TextScaled"] = true;
G2L["7b"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["7b"]["TextSize"] = 14;
G2L["7b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7b"]["Size"] = UDim2.new(0, 42, 0, 13);
G2L["7b"]["Name"] = [[-]];
G2L["7b"]["Text"] = [[-]];
G2L["7b"]["Position"] = UDim2.new(0.21776017546653748, 0, 0.11577395349740982, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.-.LocalScript
G2L["7c"] = Instance.new("LocalScript", G2L["7b"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.|
G2L["7d"] = Instance.new("TextButton", G2L["6"]);
G2L["7d"]["TextWrapped"] = true;
G2L["7d"]["BorderSizePixel"] = 0;
G2L["7d"]["TextScaled"] = true;
G2L["7d"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["7d"]["TextSize"] = 14;
G2L["7d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7d"]["Size"] = UDim2.new(0, 42, 0, 12);
G2L["7d"]["Name"] = [[|]];
G2L["7d"]["Text"] = [[|]];
G2L["7d"]["Position"] = UDim2.new(0.3357226550579071, 0, 0.11823778599500656, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.|.LocalScript
G2L["7e"] = Instance.new("LocalScript", G2L["7d"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.(
G2L["7f"] = Instance.new("TextButton", G2L["6"]);
G2L["7f"]["TextWrapped"] = true;
G2L["7f"]["BorderSizePixel"] = 0;
G2L["7f"]["TextScaled"] = true;
G2L["7f"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["7f"]["TextSize"] = 14;
G2L["7f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["7f"]["Size"] = UDim2.new(0, 42, 0, 12);
G2L["7f"]["Name"] = [[(]];
G2L["7f"]["Text"] = [[(]];
G2L["7f"]["Position"] = UDim2.new(0.4402802884578705, 0, 0.11823778599500656, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.(.LocalScript
G2L["80"] = Instance.new("LocalScript", G2L["7f"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.)
G2L["81"] = Instance.new("TextButton", G2L["6"]);
G2L["81"]["TextWrapped"] = true;
G2L["81"]["BorderSizePixel"] = 0;
G2L["81"]["TextScaled"] = true;
G2L["81"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["81"]["TextSize"] = 14;
G2L["81"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["81"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["81"]["Size"] = UDim2.new(0, 42, 0, 12);
G2L["81"]["Name"] = [[)]];
G2L["81"]["Text"] = [[)]];
G2L["81"]["Position"] = UDim2.new(0.5528808236122131, 0, 0.11823778599500656, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.).LocalScript
G2L["82"] = Instance.new("LocalScript", G2L["81"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.[
G2L["83"] = Instance.new("TextButton", G2L["6"]);
G2L["83"]["TextWrapped"] = true;
G2L["83"]["BorderSizePixel"] = 0;
G2L["83"]["TextScaled"] = true;
G2L["83"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["83"]["TextSize"] = 14;
G2L["83"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["83"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["83"]["Size"] = UDim2.new(0, 42, 0, 12);
G2L["83"]["Name"] = [[[]];
G2L["83"]["Text"] = [[[]];
G2L["83"]["Position"] = UDim2.new(0.6628003716468811, 0, 0.11823778599500656, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.[.LocalScript
G2L["84"] = Instance.new("LocalScript", G2L["83"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.]
G2L["85"] = Instance.new("TextButton", G2L["6"]);
G2L["85"]["TextWrapped"] = true;
G2L["85"]["BorderSizePixel"] = 0;
G2L["85"]["TextScaled"] = true;
G2L["85"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["85"]["TextSize"] = 14;
G2L["85"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["85"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["85"]["Size"] = UDim2.new(0, 42, 0, 12);
G2L["85"]["Name"] = [[]];
G2L["85"]["Text"] = [[]];
G2L["85"]["Position"] = UDim2.new(0.7593151330947876, 0, 0.11823778599500656, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.].LocalScript
G2L["86"] = Instance.new("LocalScript", G2L["85"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.{
G2L["87"] = Instance.new("TextButton", G2L["6"]);
G2L["87"]["TextWrapped"] = true;
G2L["87"]["BorderSizePixel"] = 0;
G2L["87"]["TextScaled"] = true;
G2L["87"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["87"]["TextSize"] = 14;
G2L["87"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["87"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["87"]["Size"] = UDim2.new(0, 42, 0, 17);
G2L["87"]["Name"] = [[{]];
G2L["87"]["Text"] = [[{]];
G2L["87"]["Position"] = UDim2.new(0.3357226550579071, 0, 0.5232557058334351, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.{.LocalScript
G2L["88"] = Instance.new("LocalScript", G2L["87"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.}
G2L["89"] = Instance.new("TextButton", G2L["6"]);
G2L["89"]["TextWrapped"] = true;
G2L["89"]["BorderSizePixel"] = 0;
G2L["89"]["TextScaled"] = true;
G2L["89"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["89"]["TextSize"] = 14;
G2L["89"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["89"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["89"]["Size"] = UDim2.new(0, 42, 0, 17);
G2L["89"]["Name"] = [[}]];
G2L["89"]["Text"] = [[}]];
G2L["89"]["Position"] = UDim2.new(0.4402802884578705, 0, 0.5232557058334351, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.}.LocalScript
G2L["8a"] = Instance.new("LocalScript", G2L["89"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Esc
G2L["8b"] = Instance.new("TextButton", G2L["6"]);
G2L["8b"]["TextWrapped"] = true;
G2L["8b"]["BorderSizePixel"] = 0;
G2L["8b"]["TextScaled"] = true;
G2L["8b"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["8b"]["TextSize"] = 14;
G2L["8b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8b"]["Size"] = UDim2.new(0, 83, 0, 27);
G2L["8b"]["Name"] = [[Esc]];
G2L["8b"]["Text"] = [[Esc]];
G2L["8b"]["Position"] = UDim2.new(-0.002078958787024021, 0, 0.7884886860847473, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Esc.LocalScript
G2L["8c"] = Instance.new("LocalScript", G2L["8b"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.=
G2L["8d"] = Instance.new("TextButton", G2L["6"]);
G2L["8d"]["TextWrapped"] = true;
G2L["8d"]["BorderSizePixel"] = 0;
G2L["8d"]["TextScaled"] = true;
G2L["8d"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["8d"]["TextSize"] = 14;
G2L["8d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8d"]["Size"] = UDim2.new(0, 42, 0, 12);
G2L["8d"]["Name"] = [[=]];
G2L["8d"]["Text"] = [[=]];
G2L["8d"]["Position"] = UDim2.new(0.8665537238121033, 0, 0.11823778599500656, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.=.LocalScript
G2L["8e"] = Instance.new("LocalScript", G2L["8d"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.BackSpace
G2L["8f"] = Instance.new("TextButton", G2L["6"]);
G2L["8f"]["TextWrapped"] = true;
G2L["8f"]["BorderSizePixel"] = 0;
G2L["8f"]["TextScaled"] = true;
G2L["8f"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["8f"]["TextSize"] = 14;
G2L["8f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8f"]["Size"] = UDim2.new(0, 65, 0, 24);
G2L["8f"]["Name"] = [[BackSpace]];
G2L["8f"]["Text"] = [[BackSpace]];
G2L["8f"]["Position"] = UDim2.new(0.823658287525177, 0, 0.9097337126731873, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.BackSpace.LocalScript
G2L["90"] = Instance.new("LocalScript", G2L["8f"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Alt
G2L["91"] = Instance.new("TextButton", G2L["6"]);
G2L["91"]["TextWrapped"] = true;
G2L["91"]["BorderSizePixel"] = 0;
G2L["91"]["TextScaled"] = true;
G2L["91"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["91"]["TextSize"] = 14;
G2L["91"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["91"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["91"]["Size"] = UDim2.new(0, 62, 0, 31);
G2L["91"]["Name"] = [[Alt]];
G2L["91"]["Text"] = [[LeftAlt]];
G2L["91"]["Position"] = UDim2.new(0.6654813289642334, 0, 0.8871797919273376, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Alt.LocalScript
G2L["92"] = Instance.new("LocalScript", G2L["91"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.LeftShift
G2L["93"] = Instance.new("TextButton", G2L["6"]);
G2L["93"]["TextWrapped"] = true;
G2L["93"]["BorderSizePixel"] = 0;
G2L["93"]["TextScaled"] = true;
G2L["93"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["93"]["TextSize"] = 14;
G2L["93"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["93"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["93"]["Size"] = UDim2.new(0, 71, 0, 23);
G2L["93"]["Name"] = [[LeftShift]];
G2L["93"]["Text"] = [[LeftShift]];
G2L["93"]["Position"] = UDim2.new(0.8075725436210632, 0, 0.7996647953987122, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.LeftShift.LocalScript
G2L["94"] = Instance.new("LocalScript", G2L["93"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.LeftCtrl
G2L["95"] = Instance.new("TextButton", G2L["6"]);
G2L["95"]["TextWrapped"] = true;
G2L["95"]["BorderSizePixel"] = 0;
G2L["95"]["TextScaled"] = true;
G2L["95"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["95"]["TextSize"] = 14;
G2L["95"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["95"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["95"]["Size"] = UDim2.new(0, 64, 0, 21);
G2L["95"]["Name"] = [[LeftCtrl]];
G2L["95"]["Text"] = [[LeftCtrl]];
G2L["95"]["Position"] = UDim2.new(0.6145430207252502, 0, 0.8100005388259888, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.LeftCtrl.LocalScript
G2L["96"] = Instance.new("LocalScript", G2L["95"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Del
G2L["97"] = Instance.new("TextButton", G2L["6"]);
G2L["97"]["TextWrapped"] = true;
G2L["97"]["BorderSizePixel"] = 0;
G2L["97"]["TextScaled"] = true;
G2L["97"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["97"]["TextSize"] = 14;
G2L["97"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["97"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["97"]["Size"] = UDim2.new(0, 42, 0, 14);
G2L["97"]["Name"] = [[Del]];
G2L["97"]["Text"] = [[Delete]];
G2L["97"]["Position"] = UDim2.new(0.6628004312515259, 0, 0.5323410630226135, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Del.LocalScript
G2L["98"] = Instance.new("LocalScript", G2L["97"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Ins
G2L["99"] = Instance.new("TextButton", G2L["6"]);
G2L["99"]["TextWrapped"] = true;
G2L["99"]["BorderSizePixel"] = 0;
G2L["99"]["TextScaled"] = true;
G2L["99"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["99"]["TextSize"] = 14;
G2L["99"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["99"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["99"]["Size"] = UDim2.new(0, 42, 0, 14);
G2L["99"]["Name"] = [[Ins]];
G2L["99"]["Text"] = [[Insert]];
G2L["99"]["Position"] = UDim2.new(0.5582427382469177, 0, 0.5323410630226135, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Ins.LocalScript
G2L["9a"] = Instance.new("LocalScript", G2L["99"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Caps
G2L["9b"] = Instance.new("TextButton", G2L["6"]);
G2L["9b"]["TextWrapped"] = true;
G2L["9b"]["BorderSizePixel"] = 0;
G2L["9b"]["TextScaled"] = true;
G2L["9b"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["9b"]["TextSize"] = 14;
G2L["9b"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9b"]["Size"] = UDim2.new(0, 36, 0, 39);
G2L["9b"]["Name"] = [[Caps]];
G2L["9b"]["Text"] = [[Caps Lock]];
G2L["9b"]["Position"] = UDim2.new(0.23384597897529602, 0, 0.486794650554657, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Caps.LocalScript
G2L["9c"] = Instance.new("LocalScript", G2L["9b"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Dollar
G2L["9d"] = Instance.new("TextButton", G2L["6"]);
G2L["9d"]["TextWrapped"] = true;
G2L["9d"]["BorderSizePixel"] = 0;
G2L["9d"]["TextScaled"] = true;
G2L["9d"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["9d"]["TextSize"] = 14;
G2L["9d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9d"]["Size"] = UDim2.new(0, 37, 0, 27);
G2L["9d"]["Name"] = [[Dollar]];
G2L["9d"]["Text"] = [[Dollar]];
G2L["9d"]["Position"] = UDim2.new(0.4468752443790436, 0, 0.7896980047225952, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Dollar.LocalScript
G2L["9e"] = Instance.new("LocalScript", G2L["9d"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.Dollar
G2L["9f"] = Instance.new("TextButton", G2L["6"]);
G2L["9f"]["TextWrapped"] = true;
G2L["9f"]["BorderSizePixel"] = 0;
G2L["9f"]["TextScaled"] = true;
G2L["9f"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["9f"]["TextSize"] = 14;
G2L["9f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["9f"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["9f"]["Size"] = UDim2.new(0, 33, 0, 27);
G2L["9f"]["Name"] = [[Dollar]];
G2L["9f"]["Text"] = [[Euro]];
G2L["9f"]["Position"] = UDim2.new(0.5385425686836243, 0, 0.7930202484130859, 0);

-- StarterGui.GuiByNor.KeyUI.Buttons.Dollar.LocalScript
G2L["a0"] = Instance.new("LocalScript", G2L["9f"]);


-- StarterGui.GuiByNor.KeyUI.Open/CloseKillGui
G2L["a1"] = Instance.new("TextButton", G2L["2"]);
G2L["a1"]["TextWrapped"] = true;
G2L["a1"]["BorderSizePixel"] = 0;
G2L["a1"]["TextScaled"] = true;
G2L["a1"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a1"]["TextSize"] = 5;
G2L["a1"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a1"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a1"]["Size"] = UDim2.new(0, 50, 0, 10);
G2L["a1"]["Name"] = [[Open/CloseKillGui]];
G2L["a1"]["Text"] = [[Open Kill Script]];
G2L["a1"]["Position"] = UDim2.new(0.033364735543727875, 0, 0.9298434257507324, 0);

-- StarterGui.GuiByNor.KeyUI.Open/CloseKillGui.LocalScript
G2L["a2"] = Instance.new("LocalScript", G2L["a1"]);


-- StarterGui.GuiByNor.KeyUI.KILLBUTTON
G2L["a3"] = Instance.new("TextButton", G2L["2"]);
G2L["a3"]["TextWrapped"] = true;
G2L["a3"]["BorderSizePixel"] = 0;
G2L["a3"]["TextScaled"] = true;
G2L["a3"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a3"]["TextSize"] = 14;
G2L["a3"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a3"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a3"]["Visible"] = false;
G2L["a3"]["Size"] = UDim2.new(0, 90, 0, 16);
G2L["a3"]["Name"] = [[KILLBUTTON]];
G2L["a3"]["Text"] = [[KILL THE SCRIPT]];
G2L["a3"]["Position"] = UDim2.new(0.3622449040412903, 0, 0.9298434257507324, 0);

-- StarterGui.GuiByNor.KeyUI.KILLBUTTON.LocalScript
G2L["a4"] = Instance.new("LocalScript", G2L["a3"]);


-- StarterGui.GuiByNor.KeyUI.LocalScript
G2L["a5"] = Instance.new("LocalScript", G2L["2"]);


-- StarterGui.GuiByNor.Open/Close
G2L["a6"] = Instance.new("TextButton", G2L["1"]);
G2L["a6"]["TextWrapped"] = true;
G2L["a6"]["BorderSizePixel"] = 0;
G2L["a6"]["TextScaled"] = true;
G2L["a6"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a6"]["TextSize"] = 5;
G2L["a6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a6"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a6"]["Size"] = UDim2.new(0, 50, 0, 20);
G2L["a6"]["Name"] = [[Open/Close]];
G2L["a6"]["Text"] = [[Open]];
G2L["a6"]["Position"] = UDim2.new(0, 0, 0.5150300860404968, 0);

-- StarterGui.GuiByNor.Open/Close.LocalScript
G2L["a7"] = Instance.new("LocalScript", G2L["a6"]);

-- StarterGui.GuiByNor.Page2button.LocalScript
G2L["a9"] = Instance.new("LocalScript", G2L["a8"]);


-- StarterGui.GuiByNor.Page2F
G2L["aa"] = Instance.new("Frame", G2L["1"]);
G2L["aa"]["BorderSizePixel"] = 0;
G2L["aa"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["aa"]["Size"] = UDim2.new(0, 372, 0, 265);
G2L["aa"]["Position"] = UDim2.new(0.41883519291877747, 0, 0.2124248445034027, 0);
G2L["aa"]["Visible"] = false;
G2L["aa"]["Name"] = [[Page2F]];

-- StarterGui.GuiByNor.Page2F.TextLabel
G2L["ab"] = Instance.new("TextLabel", G2L["aa"]);
G2L["ab"]["TextWrapped"] = true;
G2L["ab"]["BorderSizePixel"] = 0;
G2L["ab"]["TextScaled"] = true;
G2L["ab"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["ab"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["ab"]["TextSize"] = 14;
G2L["ab"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ab"]["Size"] = UDim2.new(0, 200, 0, 22);
G2L["ab"]["Text"] = [[Page 2]];
G2L["ab"]["Position"] = UDim2.new(0.2016129046678543, 0, 0, 0);

-- StarterGui.GuiByNor.Page2F.*
G2L["ac"] = Instance.new("TextButton", G2L["aa"]);
G2L["ac"]["TextWrapped"] = true;
G2L["ac"]["BorderSizePixel"] = 0;
G2L["ac"]["TextScaled"] = true;
G2L["ac"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["ac"]["TextSize"] = 14;
G2L["ac"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["ac"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ac"]["Size"] = UDim2.new(0, 37, 0, 33);
G2L["ac"]["Name"] = [[*]];
G2L["ac"]["Text"] = [[*]];
G2L["ac"]["Position"] = UDim2.new(0.019700245931744576, 0, 0.11998336762189865, 0);

-- StarterGui.GuiByNor.Page2F.*.LocalScript
G2L["ad"] = Instance.new("LocalScript", G2L["ac"]);


-- StarterGui.GuiByNor.Page2F.?
G2L["ae"] = Instance.new("TextButton", G2L["aa"]);
G2L["ae"]["TextWrapped"] = true;
G2L["ae"]["BorderSizePixel"] = 0;
G2L["ae"]["TextScaled"] = true;
G2L["ae"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["ae"]["TextSize"] = 14;
G2L["ae"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["ae"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ae"]["Size"] = UDim2.new(0, 37, 0, 33);
G2L["ae"]["Name"] = [[?]];
G2L["ae"]["Text"] = [[?]];
G2L["ae"]["Position"] = UDim2.new(0.11916261166334152, 0, 0.11998336762189865, 0);

-- StarterGui.GuiByNor.Page2F.?.LocalScript
G2L["af"] = Instance.new("LocalScript", G2L["ae"]);


-- StarterGui.GuiByNor.Page2F.`
G2L["b0"] = Instance.new("TextButton", G2L["aa"]);
G2L["b0"]["TextWrapped"] = true;
G2L["b0"]["BorderSizePixel"] = 0;
G2L["b0"]["TextScaled"] = true;
G2L["b0"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["b0"]["TextSize"] = 14;
G2L["b0"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b0"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b0"]["Size"] = UDim2.new(0, 37, 0, 33);
G2L["b0"]["Name"] = [[`]];
G2L["b0"]["Text"] = [[`]];
G2L["b0"]["Position"] = UDim2.new(0.21324864029884338, 0, 0.12375695258378983, 0);

-- StarterGui.GuiByNor.Page2F.`.LocalScript
G2L["b1"] = Instance.new("LocalScript", G2L["b0"]);


-- StarterGui.GuiByNor.Page2F.<
G2L["b2"] = Instance.new("TextButton", G2L["aa"]);
G2L["b2"]["TextWrapped"] = true;
G2L["b2"]["BorderSizePixel"] = 0;
G2L["b2"]["TextScaled"] = true;
G2L["b2"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["b2"]["TextSize"] = 14;
G2L["b2"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b2"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b2"]["Size"] = UDim2.new(0, 37, 0, 33);
G2L["b2"]["Name"] = [[<]];
G2L["b2"]["Text"] = [[<]];
G2L["b2"]["Position"] = UDim2.new(0.39066800475120544, 0, 0.7388513088226318, 0);

-- StarterGui.GuiByNor.Page2F.<.LocalScript
G2L["b3"] = Instance.new("LocalScript", G2L["b2"]);


-- StarterGui.GuiByNor.Page2F.>
G2L["b4"] = Instance.new("TextButton", G2L["aa"]);
G2L["b4"]["TextWrapped"] = true;
G2L["b4"]["BorderSizePixel"] = 0;
G2L["b4"]["TextScaled"] = true;
G2L["b4"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["b4"]["TextSize"] = 14;
G2L["b4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b4"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b4"]["Size"] = UDim2.new(0, 37, 0, 33);
G2L["b4"]["Name"] = [[>]];
G2L["b4"]["Text"] = [[>]];
G2L["b4"]["Position"] = UDim2.new(0.5680873394012451, 0, 0.7388513088226318, 0);

-- StarterGui.GuiByNor.Page2F.>.LocalScript
G2L["b5"] = Instance.new("LocalScript", G2L["b4"]);


-- StarterGui.GuiByNor.Page2F.Up
G2L["b6"] = Instance.new("TextButton", G2L["aa"]);
G2L["b6"]["TextWrapped"] = true;
G2L["b6"]["BorderSizePixel"] = 0;
G2L["b6"]["TextScaled"] = true;
G2L["b6"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["b6"]["TextSize"] = 14;
G2L["b6"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b6"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b6"]["Size"] = UDim2.new(0, 37, 0, 33);
G2L["b6"]["Name"] = [[Up]];
G2L["b6"]["Text"] = [[Up]];
G2L["b6"]["Position"] = UDim2.new(0.4820658266544342, 0, 0.5916814804077148, 0);

-- StarterGui.GuiByNor.Page2F.Up.LocalScript
G2L["b7"] = Instance.new("LocalScript", G2L["b6"]);


-- StarterGui.GuiByNor.Page2F.Dovn
G2L["b8"] = Instance.new("TextButton", G2L["aa"]);
G2L["b8"]["TextWrapped"] = true;
G2L["b8"]["BorderSizePixel"] = 0;
G2L["b8"]["TextScaled"] = true;
G2L["b8"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["b8"]["TextSize"] = 14;
G2L["b8"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b8"]["Size"] = UDim2.new(0, 37, 0, 33);
G2L["b8"]["Name"] = [[Dovn]];
G2L["b8"]["Text"] = [[Down]];
G2L["b8"]["Position"] = UDim2.new(0.47668948769569397, 0, 0.8747003078460693, 0);

-- StarterGui.GuiByNor.Page2F.Dovn.LocalScript
G2L["b9"] = Instance.new("LocalScript", G2L["b8"]);


-- StarterGui.GuiByNor.Page2F.+
G2L["ba"] = Instance.new("TextButton", G2L["aa"]);
G2L["ba"]["TextWrapped"] = true;
G2L["ba"]["BorderSizePixel"] = 0;
G2L["ba"]["TextScaled"] = true;
G2L["ba"]["BackgroundColor3"] = Color3.fromRGB(64, 64, 64);
G2L["ba"]["TextSize"] = 14;
G2L["ba"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["ba"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["ba"]["Size"] = UDim2.new(0, 37, 0, 33);
G2L["ba"]["Name"] = [[+]];
G2L["ba"]["Text"] = [[+]];
G2L["ba"]["Position"] = UDim2.new(0.3127110004425049, 0, 0.11998336762189865, 0);

-- StarterGui.GuiByNor.Page2F.+.LocalScript
G2L["bb"] = Instance.new("LocalScript", G2L["ba"]);


-- StarterGui.GuiByNor.KeyUI.Buttons.W.LocalScript
local function C_8()
local script = G2L["8"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "W"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_8);
-- StarterGui.GuiByNor.KeyUI.Buttons.S.LocalScript
local function C_a()
local script = G2L["a"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "S"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_a);
-- StarterGui.GuiByNor.KeyUI.Buttons.D.LocalScript
local function C_c()
local script = G2L["c"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "D"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_c);
-- StarterGui.GuiByNor.KeyUI.Buttons.A.LocalScript
local function C_e()
local script = G2L["e"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "A"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
		end)
end;
task.spawn(C_e);
-- StarterGui.GuiByNor.KeyUI.Buttons.Q.LocalScript
local function C_10()
local script = G2L["10"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Q"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_10);
-- StarterGui.GuiByNor.KeyUI.Buttons.E.LocalScript
local function C_12()
local script = G2L["12"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "E"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_12);
-- StarterGui.GuiByNor.KeyUI.Buttons.1.LocalScript
local function C_14()
local script = G2L["14"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "One"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_14);
-- StarterGui.GuiByNor.KeyUI.Buttons.2.LocalScript
local function C_16()
local script = G2L["16"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Two"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_16);
-- StarterGui.GuiByNor.KeyUI.Buttons.3.LocalScript
local function C_18()
local script = G2L["18"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Three"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_18);
-- StarterGui.GuiByNor.KeyUI.Buttons.4.LocalScript
local function C_1a()
local script = G2L["1a"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Four"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_1a);
-- StarterGui.GuiByNor.KeyUI.Buttons.5.LocalScript
local function C_1c()
local script = G2L["1c"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Five"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_1c);
-- StarterGui.GuiByNor.KeyUI.Buttons.6.LocalScript
local function C_1e()
local script = G2L["1e"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Six"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_1e);
-- StarterGui.GuiByNor.KeyUI.Buttons.7.LocalScript
local function C_20()
local script = G2L["20"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Seven"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_20);
-- StarterGui.GuiByNor.KeyUI.Buttons.8.LocalScript
local function C_22()
local script = G2L["22"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Eight"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_22);
-- StarterGui.GuiByNor.KeyUI.Buttons.9.LocalScript
local function C_24()
local script = G2L["24"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Nine"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_24);
-- StarterGui.GuiByNor.KeyUI.Buttons.R.LocalScript
local function C_26()
local script = G2L["26"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "R"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_26);
-- StarterGui.GuiByNor.KeyUI.Buttons.T.LocalScript
local function C_28()
local script = G2L["28"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "T"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_28);
-- StarterGui.GuiByNor.KeyUI.Buttons.Y.LocalScript
local function C_2a()
local script = G2L["2a"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Y"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_2a);
-- StarterGui.GuiByNor.KeyUI.Buttons.U.LocalScript
local function C_2c()
local script = G2L["2c"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "U"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_2c);
-- StarterGui.GuiByNor.KeyUI.Buttons.I.LocalScript
local function C_2e()
local script = G2L["2e"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "I"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_2e);
-- StarterGui.GuiByNor.KeyUI.Buttons.O.LocalScript
local function C_30()
local script = G2L["30"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "O"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_30);
-- StarterGui.GuiByNor.KeyUI.Buttons.P.LocalScript
local function C_32()
local script = G2L["32"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "P"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_32);
-- StarterGui.GuiByNor.KeyUI.Buttons.F.LocalScript
local function C_34()
local script = G2L["34"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_34);
-- StarterGui.GuiByNor.KeyUI.Buttons.G.LocalScript
local function C_36()
local script = G2L["36"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "G"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_36);
-- StarterGui.GuiByNor.KeyUI.Buttons.H.LocalScript
local function C_38()
local script = G2L["38"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "H"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_38);
-- StarterGui.GuiByNor.KeyUI.Buttons.J.LocalScript
local function C_3a()
local script = G2L["3a"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "J"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_3a);
-- StarterGui.GuiByNor.KeyUI.Buttons.K.LocalScript
local function C_3c()
local script = G2L["3c"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "K"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_3c);
-- StarterGui.GuiByNor.KeyUI.Buttons.L.LocalScript
local function C_3e()
local script = G2L["3e"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "L"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_3e);
-- StarterGui.GuiByNor.KeyUI.Buttons.Z.LocalScript
local function C_40()
local script = G2L["40"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Z"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_40);
-- StarterGui.GuiByNor.KeyUI.Buttons.X.LocalScript
local function C_42()
local script = G2L["42"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "X"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_42);
-- StarterGui.GuiByNor.KeyUI.Buttons.C.LocalScript
local function C_44()
local script = G2L["44"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "C"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_44);
-- StarterGui.GuiByNor.KeyUI.Buttons.V.LocalScript
local function C_46()
local script = G2L["46"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "V"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_46);
-- StarterGui.GuiByNor.KeyUI.Buttons.B.LocalScript
local function C_48()
local script = G2L["48"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "B"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_48);
-- StarterGui.GuiByNor.KeyUI.Buttons.N.LocalScript
local function C_4a()
local script = G2L["4a"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "N"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_4a);
-- StarterGui.GuiByNor.KeyUI.Buttons.M.LocalScript
local function C_4c()
local script = G2L["4c"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "M"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_4c);
-- StarterGui.GuiByNor.KeyUI.Buttons.Shift.LocalScript
local function C_4e()
local script = G2L["4e"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "LeftShift"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_4e);
-- StarterGui.GuiByNor.KeyUI.Buttons.Tab.LocalScript
local function C_50()
local script = G2L["50"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Tab"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_50);
-- StarterGui.GuiByNor.KeyUI.Buttons.Ctrl.LocalScript
local function C_52()
local script = G2L["52"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "LeftControl"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_52);
-- StarterGui.GuiByNor.KeyUI.Buttons.Space.LocalScript
local function C_54()
local script = G2L["54"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Space"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_54);
-- StarterGui.GuiByNor.KeyUI.Buttons.LeftAlt.LocalScript
local function C_56()
local script = G2L["56"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "LeftAlt"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_56);
-- StarterGui.GuiByNor.KeyUI.Buttons.Enter.LocalScript
local function C_58()
local script = G2L["58"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "KeypadEnter"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_58);
-- StarterGui.GuiByNor.KeyUI.Buttons.F1.LocalScript
local function C_5a()
local script = G2L["5a"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F1"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_5a);
-- StarterGui.GuiByNor.KeyUI.Buttons.F2.LocalScript
local function C_5c()
local script = G2L["5c"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F2"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_5c);
-- StarterGui.GuiByNor.KeyUI.Buttons.F3.LocalScript
local function C_5e()
local script = G2L["5e"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F3"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_5e);
-- StarterGui.GuiByNor.KeyUI.Buttons.F4.LocalScript
local function C_60()
local script = G2L["60"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F4"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_60);
-- StarterGui.GuiByNor.KeyUI.Buttons.F5.LocalScript
local function C_62()
local script = G2L["62"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F5"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_62);
-- StarterGui.GuiByNor.KeyUI.Buttons.F6.LocalScript
local function C_64()
local script = G2L["64"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F6"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_64);
-- StarterGui.GuiByNor.KeyUI.Buttons.F7.LocalScript
local function C_66()
local script = G2L["66"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F7"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_66);
-- StarterGui.GuiByNor.KeyUI.Buttons.F8.LocalScript
local function C_68()
local script = G2L["68"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F8"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_68);
-- StarterGui.GuiByNor.KeyUI.Buttons.F9.LocalScript
local function C_6a()
local script = G2L["6a"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F9"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_6a);
-- StarterGui.GuiByNor.KeyUI.Buttons.F10.LocalScript
local function C_6c()
local script = G2L["6c"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F10"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_6c);
-- StarterGui.GuiByNor.KeyUI.Buttons.F11.LocalScript
local function C_6e()
local script = G2L["6e"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F11"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_6e);
-- StarterGui.GuiByNor.KeyUI.Buttons.F12.LocalScript
local function C_70()
local script = G2L["70"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "F12"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_70);
-- StarterGui.GuiByNor.KeyUI.Buttons.;.LocalScript
local function C_72()
local script = G2L["72"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = ";"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_72);
-- StarterGui.GuiByNor.KeyUI.Buttons...LocalScript
local function C_74()
local script = G2L["74"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "."
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_74);
-- StarterGui.GuiByNor.KeyUI.Buttons.,.LocalScript
local function C_76()
local script = G2L["76"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = ","
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_76);
-- StarterGui.GuiByNor.KeyUI.Buttons./.LocalScript
local function C_78()
local script = G2L["78"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Slash"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_78);
-- StarterGui.GuiByNor.KeyUI.Buttons.+.LocalScript
local function C_7a()
local script = G2L["7a"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "+"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_7a);
-- StarterGui.GuiByNor.KeyUI.Buttons.-.LocalScript
local function C_7c()
local script = G2L["7c"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "-"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_7c);
-- StarterGui.GuiByNor.KeyUI.Buttons.|.LocalScript
local function C_7e()
local script = G2L["7e"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "|"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_7e);
-- StarterGui.GuiByNor.KeyUI.Buttons.(.LocalScript
local function C_80()
local script = G2L["80"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "LeftParenthesis"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_80);
-- StarterGui.GuiByNor.KeyUI.Buttons.).LocalScript
local function C_82()
local script = G2L["82"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "RightParenthesis"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_82);
-- StarterGui.GuiByNor.KeyUI.Buttons.[.LocalScript
local function C_84()
local script = G2L["84"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "["
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_84);
-- StarterGui.GuiByNor.KeyUI.Buttons.].LocalScript
local function C_86()
local script = G2L["86"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "]"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_86);
-- StarterGui.GuiByNor.KeyUI.Buttons.{.LocalScript
local function C_88()
local script = G2L["88"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "{"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_88);
-- StarterGui.GuiByNor.KeyUI.Buttons.}.LocalScript
local function C_8a()
local script = G2L["8a"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "}"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_8a);
-- StarterGui.GuiByNor.KeyUI.Buttons.Esc.LocalScript
local function C_8c()
local script = G2L["8c"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Espace"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_8c);
-- StarterGui.GuiByNor.KeyUI.Buttons.=.LocalScript
local function C_8e()
local script = G2L["8e"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Equals"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_8e);
-- StarterGui.GuiByNor.KeyUI.Buttons.BackSpace.LocalScript
local function C_90()
local script = G2L["90"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Backspace"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_90);
-- StarterGui.GuiByNor.KeyUI.Buttons.Alt.LocalScript
local function C_92()
local script = G2L["92"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "RightAlt"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_92);
-- StarterGui.GuiByNor.KeyUI.Buttons.LeftShift.LocalScript
local function C_94()
local script = G2L["94"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "RightShift"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_94);
-- StarterGui.GuiByNor.KeyUI.Buttons.LeftCtrl.LocalScript
local function C_96()
local script = G2L["96"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "RightControl"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_96);
-- StarterGui.GuiByNor.KeyUI.Buttons.Del.LocalScript
local function C_98()
local script = G2L["98"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Delete"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_98);
-- StarterGui.GuiByNor.KeyUI.Buttons.Ins.LocalScript
local function C_9a()
local script = G2L["9a"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Insert"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_9a);
-- StarterGui.GuiByNor.KeyUI.Buttons.Caps.LocalScript
local function C_9c()
local script = G2L["9c"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "CapsLock"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_9c);
-- StarterGui.GuiByNor.KeyUI.Buttons.Dollar.LocalScript
local function C_9e()
local script = G2L["9e"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Dollar"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_9e);
-- StarterGui.GuiByNor.KeyUI.Buttons.Dollar.LocalScript
local function C_a0()
local script = G2L["a0"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Dollar"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_a0);
-- StarterGui.GuiByNor.KeyUI.Open/CloseKillGui.LocalScript
local function C_a2()
local script = G2L["a2"];
	script.Parent.MouseButton1Click:Connect(function()
		
		if script.Parent.Parent.KILLBUTTON.Visible == true then
			script.Parent.Parent.KILLBUTTON.Visible = false
			script.Parent.Text = "Open Kill Script"
		else
			script.Parent.Parent.KILLBUTTON.Visible = true
			script.Parent.Text = "Hide SKill Script"
		end
	end)
end;
task.spawn(C_a2);
-- StarterGui.GuiByNor.KeyUI.KILLBUTTON.LocalScript
local function C_a4()
local script = G2L["a4"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Parent.GuiByNor:Destroy()
	end)
end;
task.spawn(C_a4);
-- StarterGui.GuiByNor.KeyUI.LocalScript
local function C_a5()
local script = G2L["a5"];
	script.Parent.Active = true
	script.Parent.Selectable = true
	script.Parent.Draggable = true
end;
task.spawn(C_a5);
-- StarterGui.GuiByNor.Open/Close.LocalScript
local function C_a7()
local script = G2L["a7"];
	script.Parent.MouseButton1Click:Connect(function()
		
		if script.Parent.Parent.KeyUI.Visible == true then
			script.Parent.Parent.KeyUI.Visible = false
			script.Parent.Text = "Open"
		else
			script.Parent.Parent.KeyUI.Visible = true
			script.Parent.Text = "Close"
		end
	end)
end;
task.spawn(C_a7);
-- StarterGui.GuiByNor.Page2button.LocalScript
local function C_a9()
local script = G2L["a9"];
	script.Parent.MouseButton1Click:Connect(function()
		
		if script.Parent.Parent.Page2F.Visible == true then
			script.Parent.Parent.Page2F.Visible = false
			script.Parent.Text = "Open Page 2"
		else
			script.Parent.Parent.Page2F.Visible = true
			script.Parent.Text = "Close Page 2"
		end
	end)
end;
task.spawn(C_a9);
-- StarterGui.GuiByNor.Page2F.*.LocalScript
local function C_ad()
local script = G2L["ad"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Asterisk"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_ad);
-- StarterGui.GuiByNor.Page2F.?.LocalScript
local function C_af()
local script = G2L["af"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Question"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_af);
-- StarterGui.GuiByNor.Page2F.`.LocalScript
local function C_b1()
local script = G2L["b1"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Backquote"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_b1);
-- StarterGui.GuiByNor.Page2F.<.LocalScript
local function C_b3()
local script = G2L["b3"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Right"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_b3);
-- StarterGui.GuiByNor.Page2F.>.LocalScript
local function C_b5()
local script = G2L["b5"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Left"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_b5);
-- StarterGui.GuiByNor.Page2F.Up.LocalScript
local function C_b7()
local script = G2L["b7"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Up"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_b7);
-- StarterGui.GuiByNor.Page2F.Dovn.LocalScript
local function C_b9()
local script = G2L["b9"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Down"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_b9);
-- StarterGui.GuiByNor.Page2F.+.LocalScript
local function C_bb()
local script = G2L["bb"];
	script.Parent.MouseButton1Down:Connect(function()
		getfenv().keytoclick = "Plus"
		local vim = game:service("VirtualInputManager")
		vim:SendKeyEvent(true, keytoclick, false, game)
	end)
end;
task.spawn(C_bb);

return G2L["1"], require;
