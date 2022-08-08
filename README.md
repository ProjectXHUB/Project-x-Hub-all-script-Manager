local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Project x Hub all script Manager", "DarkTheme")

local Tab = Window:NewTab("Free style")
local Section = Tab:NewSection("Pino")
Section:NewButton("Execute", "ButtonInfo", function()
    --[[Subscribe to Zaptosis on YouTube for more awesome scripts!
Join our Discord: www.zaptosis.weebly.com
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
███▀▀▀███░░░░░░░░░░░░░░░░░░░██░░░░░░░░░░░░░░░░░░░░██░░░░░░░░░
█▀░░░███░░░░░░░░░░░░░░░░░░░░██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
▀░░░███░░▄█▀██▄░▀████████▄██████░░▄██▀██▄░▄██▀██████░░▄██▀███
░░░███░░██░░░██░░░██░░░▀██░░██░░░██▀░░░▀████░░░▀▀░██░░██░░░▀▀
░░███░░░▄▄█████░░░██░░░░██░░██░░░██░░░░░██▀█████▄░██░░▀█████▄
░███░░░▄██░░░██░░░██░░░▄██░░██░░░██▄░░░▄███▄░░░██░██░░█▄░░░██
█████████████▀██▄░██████▀░░░▀████░▀█████▀░██████▀████▄██████▀
░░░░░░░░░░░░░░░░░░██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░░░░░░░░░░░▄████▄░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
]]
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/richie0866/MidiPlayer/main/package.lua"))()
end)

local Tab = Window:NewTab("Avatar Script")
local Section = Tab:NewSection("Bike")
Section:NewButton("Execute", "ButtonInfo", function()
    --MADE BY GUAVAJUICEFANCLUBFAN (Delectiv#1857)
--SUBSCRIBE TO DARK ECCENTRIC
--HATS NEEDED--
--https://www.roblox.com/catalog/9743558381/TJ-Wearable-BMX-Backpack
--HAT IS VERY EASY TO GET, YOU GET IT UNDER 30SECONDS GAME LINK TO GET https://www.roblox.com/games/9129288160/Tommy-Play

game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 50
clickfling = false -- set this to false if u dont want click fling or use torso flin
function rmesh(a)
if not (workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('Mesh') or workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('SpecialMesh')) then return end
old=game.Players.LocalPlayer.Character
game.Players.LocalPlayer.Character=workspace[game.Players.LocalPlayer.Name]
for i,v in next, workspace[game.Players.LocalPlayer.Name]:FindFirstChild(a).Handle:GetDescendants() do
if v:IsA('Mesh') or v:IsA('SpecialMesh') then
v:Remove()
end
end
for i = 1 , 2 do
game.Players.LocalPlayer.Character=old
end
end

a=game.Players.LocalPlayer b=game.Players.LocalPlayer.Character c={}d=table.insert e=false for D,E in next,game:GetService("Players").LocalPlayer.Character:GetDescendants()do if E:IsA("BasePart")then d(c,game:GetService("RunService").Heartbeat:connect(function()pcall(function()E.Velocity=Vector3.new(-30,0,0)sethiddenproperty(game.Players.LocalPlayer,"MaximumSimulationRadius",math.huge)sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",999999999)game.Players.LocalPlayer.ReplicationFocus=workspace end)end))end end function f(D,E,F)game.StarterGui:SetCore("SendNotification",{Title=D;Text=E;Duration=F or 5;})end local x=game:GetService("RunService")g=Instance.new('Folder',b)g.Name='CWExtra'b.Archivable=true local y=b:Clone()y.Name='NexoPD'for D,E in next,y:GetDescendants()do if E:IsA('BasePart')or E:IsA('Decal')then E.Transparency=1 end end h=5.65 a.Character=nil a.Character=b b.Humanoid.AutoRotate=false b.Humanoid.WalkSpeed=0 b.Humanoid.JumpPower=0 b.Torso.Anchored=true f('Nexo','Reanimating...\nPlease wait '..h..' seconds.')wait(h)b.Torso.Anchored=false f('Nexo','Reanimated..')b.Humanoid.Health=0 y.Animate.Disabled=true y.Parent=g y.HumanoidRootPart.CFrame=b.HumanoidRootPart.CFrame*CFrame.new(0,5,0)function i(D,E,F,G)Instance.new("Attachment",D)Instance.new("AlignPosition",D)Instance.new("AlignOrientation",D)Instance.new("Attachment",E)D.Attachment.Name=D.Name E.Attachment.Name=D.Name D.AlignPosition.Attachment0=D[D.Name]D.AlignOrientation.Attachment0=D[D.Name]D.AlignPosition.Attachment1=E[D.Name]D.AlignOrientation.Attachment1=E[D.Name]E[D.Name].Position=F or Vector3.new()D[D.Name].Orientation=G or Vector3.new()D.AlignPosition.MaxForce=999999999 D.AlignPosition.MaxVelocity=math.huge D.AlignPosition.ReactionForceEnabled=false D.AlignPosition.Responsiveness=math.huge D.AlignOrientation.Responsiveness=math.huge D.AlignPosition.RigidityEnabled=false D.AlignOrientation.MaxTorque=999999999 D.Massless=true end function j(D,E,F)Instance.new("Attachment",D)Instance.new("AlignPosition",D)Instance.new("Attachment",E)D.Attachment.Name=D.Name E.Attachment.Name=D.Name D.AlignPosition.Attachment0=D[D.Name]D.AlignPosition.Attachment1=E[D.Name]E[D.Name].Position=F or Vector3.new()D.AlignPosition.MaxForce=999999999 D.AlignPosition.MaxVelocity=math.huge D.AlignPosition.ReactionForceEnabled=false D.AlignPosition.Responsiveness=math.huge D.Massless=true end for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then d(c,x.RenderStepped:Connect(function()E.CanCollide=false end))end end for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then d(c,x.Stepped:Connect(function()E.CanCollide=false end))end end for D,E in next,y:GetDescendants()do if E:IsA('BasePart')then d(c,x.RenderStepped:Connect(function()E.CanCollide=false end))end end for D,E in next,y:GetDescendants()do if E:IsA('BasePart')then d(c,x.Stepped:Connect(function()E.CanCollide=false end))end end for D,E in next,b:GetDescendants()do if E:IsA('Accessory')then i(E.Handle,y[E.Name].Handle)end end i(b['Head'],y['Head'])i(b['Torso'],y['Torso'])j(b['HumanoidRootPart'],y['Torso'],Vector3.new(0,0,0))i(b['Right Arm'],y['Right Arm'])i(b['Left Arm'],y['Left Arm'])i(b['Right Leg'],y['Right Leg'])i(b['Left Leg'],y['Left Leg'])k=a:GetMouse()local z=Instance.new("Part",g)z.CanCollide=false z.Transparency=1 d(c,x.RenderStepped:Connect(function()local D=workspace.CurrentCamera.CFrame.lookVector local E=y["HumanoidRootPart"]z.Position=E.Position z.CFrame=CFrame.new(z.Position,Vector3.new(D.X*10000,D.Y,D.Z*10000))end))l=false m=false n=false o=false p=false function q(D)r=Instance.new('BodyAngularVelocity',D)r.AngularVelocity=Vector3.new(9e9,9e9,9e9)r.MaxTorque=Vector3.new(9e9,9e9,9e9)end q(b.HumanoidRootPart)k=a:GetMouse()s=Instance.new('BodyPosition',b.HumanoidRootPart)s.P=9e9 s.D=9e9 s.MaxForce=Vector3.new(99999,99999,99999)local A d(c,x.Heartbeat:Connect(function()if A==true then s.Position=k.Hit.p b.HumanoidRootPart.Position=k.Hit.p else s.Position=y.Torso.Position b.HumanoidRootPart.Position=y.Torso.Position end end))local B=Instance.new("SelectionBox")B.Adornee=b.HumanoidRootPart B.LineThickness=0.02 B.Color3=Color3.fromRGB(250,0,0)B.Parent=b.HumanoidRootPart B.Name="RAINBOW"t=B if clickfling then d(c,k.Button1Down:Connect(function()A=true end))d(c,k.Button1Up:Connect(function()A=false end))end d(c,k.KeyDown:Connect(function(D)if D==' 'then p=true end if D=='w'then l=true end if D=='s'then m=true end if D=='a'then n=true end if D=='d'then o=true end end))d(c,k.KeyUp:Connect(function(D)if D==' 'then p=false end if D=='w'then l=false end if D=='s'then m=false end if D=='a'then n=false end if D=='d'then o=false end end))local function C(D,E,F)z.CFrame=z.CFrame*CFrame.new(-D,E,-F)y.Humanoid.WalkToPoint=z.Position end d(c,x.RenderStepped:Connect(function()if l==true then C(0,0,1e4)end if m==true then C(0,0,-1e4)end if n==true then C(1e4,0,0)end if o==true then C(-1e4,0,0)end if p==true then y.Humanoid.Jump=true end if l~=true and n~=true and m~=true and o~=true then y.Humanoid.WalkToPoint=y.HumanoidRootPart.Position end end))workspace.CurrentCamera.CameraSubject=y.Humanoid u=Instance.new('BindableEvent')d(c,u.Event:Connect(function()y:Destroy()e=true v=false for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then E.Anchored=true end end w=b.Humanoid:Clone()b.Humanoid:Destroy()w.Parent=b game.Players:Chat('-re')for D,E in pairs(c)do E:Disconnect()end game:GetService("StarterGui"):SetCore("ResetButtonCallback",true)u:Remove()end))game:GetService("StarterGui"):SetCore("ResetButtonCallback",u)

IT = Instance.new
CF = CFrame.new
VT = Vector3.new
RAD = math.rad
C3 = Color3.new
UD2 = UDim2.new
BRICKC = BrickColor.new
ANGLES = CFrame.Angles
EULER = CFrame.fromEulerAnglesXYZ
COS = math.cos
ACOS = math.acos
SIN = math.sin
ASIN = math.asin
ABS = math.abs
MRANDOM = math.random
FLOOR = math.floor

speed = 1
sine = 1
srv = game:GetService('RunService')

reanim = workspace.Camera.CameraSubject.Parent

function hat(h,p,c1,c0,m)
reanim[h].Handle.AccessoryWeld.Part1=reanim[p]
reanim[h].Handle.AccessoryWeld.C1=c1 or CFrame.new()
reanim[h].Handle.AccessoryWeld.C0=reanim[h].Handle.AccessoryWeld.C0:Lerp(c0 or CFrame.new(),1)
if m == true then
rmesh(h)
end
end

m=game.Players.LocalPlayer:GetMouse()
RJ = reanim.HumanoidRootPart.RootJoint
RS = reanim.Torso['Right Shoulder']
LS = reanim.Torso['Left Shoulder']
RH = reanim.Torso['Right Hip']
LH = reanim.Torso['Left Hip']
Root = reanim.HumanoidRootPart
NECK = reanim.Torso.Neck
NECK.C0 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
NECK.C1 = CF(0,-0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C1 = CF(0,-1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))

Mode='1'

mousechanger=game.Players.LocalPlayer:GetMouse().KeyDown:Connect(function(k)
if k == '1' then-- first mode
Mode='1'
elseif k == 'e' then-- second mode
Mode='2'
elseif k == 'q' then-- first mode again
Mode='1'
end
end)

attacklol=game.Players.LocalPlayer:GetMouse().Button1Down:Connect(function()
Mode='Attack1'
wait(0.5) -- time of attack u can edit this
Mode='Attack2'
wait(0.5)
Mode='Attack3'
wait(0.5)
Mode ='2' -- change this mode to whatever u want the mode to be after attacking
end)

coroutine.wrap(function()
while true do -- anim changer
if HumanDied then break end
sine = sine + speed
local rlegray = Ray.new(reanim["Right Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local rlegpart, rlegendPoint = workspace:FindPartOnRay(rlegray, char)
local llegray = Ray.new(reanim["Left Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local llegpart, llegendPoint = workspace:FindPartOnRay(llegray, char)
local rightvector = (Root.Velocity * Root.CFrame.rightVector).X + (Root.Velocity * Root.CFrame.rightVector).Z
local lookvector = (Root.Velocity * Root.CFrame.lookVector).X + (Root.Velocity * Root.CFrame.lookVector).Z
if lookvector > reanim.Humanoid.WalkSpeed then
lookvector = reanim.Humanoid.WalkSpeed
end
if lookvector < -reanim.Humanoid.WalkSpeed then
lookvector = -reanim.Humanoid.WalkSpeed
end
if rightvector > reanim.Humanoid.WalkSpeed then
rightvector = reanim.Humanoid.WalkSpeed
end
if rightvector < -reanim.Humanoid.WalkSpeed then
rightvector = -reanim.Humanoid.WalkSpeed
end
local lookvel = lookvector / reanim.Humanoid.WalkSpeed
local rightvel = rightvector / reanim.Humanoid.WalkSpeed
if Mode == '1' then
if Root.Velocity.y > 1 then -- jump
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0.57+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-32.62+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-33.6+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(33.6+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Back Bike','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),2+0*math["cos"](sine/10),-0.5+0*math["cos"](sine/10))*CFrame.Angles(math.rad(53.98+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
elseif Root.Velocity.y < -1 then -- fall
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0.57+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-32.62+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-33.6+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(33.6+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Back Bike','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),2+0*math["cos"](sine/10),-0.5+0*math["cos"](sine/10))*CFrame.Angles(math.rad(53.98+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)

elseif Root.Velocity.Magnitude < 2 then -- idle
hat('Back Bike','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),1.8+0*math["cos"](sine/10),-0.86+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-8+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-2.06+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-7.15+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(110.02+0*math.cos(sine/10)),math.rad(23.42+0*math.cos(sine/10)),math.rad(-32.62+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(110.02+0*math.cos(sine/10)),math.rad(-23.42+0*math.cos(sine/10)),math.rad(32.62+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1.4+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(13.23+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),-1.22+0*math.cos(sine/10))*CFrame.Angles(math.rad(-63.19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

elseif Root.Velocity.Magnitude > 20 then -- run
hat('Back Bike','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),1.8+0*math["cos"](sine/10),-0.86+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-8+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+-2.06*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-2.06+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(110.02+0*math.cos(sine/10)),math.rad(23.42+0*math.cos(sine/10)),math.rad(-32.62+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(110.02+0*math.cos(sine/10)),math.rad(-23.42+0*math.cos(sine/10)),math.rad(32.62+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0.6*math.cos(sine/10),0+0.5*math.cos(sine/10))*CFrame.Angles(math.rad(0+79.46*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.6*math.cos(sine/10),0+-0.5*math.cos(sine/10))*CFrame.Angles(math.rad(0+-79.46*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)

elseif Root.Velocity.Magnitude < 20 then -- walk
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0.57+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-32.62+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-33.6+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(33.6+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Back Bike','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),2+0*math["cos"](sine/10),-0.5+0*math["cos"](sine/10))*CFrame.Angles(math.rad(53.98+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)

end

elseif Mode == '2' then
if Root.Velocity.y > 1 then -- jump
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0.57+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-32.62+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-33.6+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(33.6+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Back Bike','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),2+0*math["cos"](sine/10),-0.5+0*math["cos"](sine/10))*CFrame.Angles(math.rad(53.98+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
elseif Root.Velocity.y < -1 then -- fall
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0.57+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-32.62+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-33.6+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(33.6+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Back Bike','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),2+0*math["cos"](sine/10),-0.5+0*math["cos"](sine/10))*CFrame.Angles(math.rad(53.98+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)

elseif Root.Velocity.Magnitude < 2 then -- idle
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0.25+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-65+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-33.6+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(33.6+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-1.22+0*math.cos(sine/10))*CFrame.Angles(math.rad(38.7+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-1.58+0*math.cos(sine/10))*CFrame.Angles(math.rad(-12.25+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Back Bike','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),2+0*math["cos"](sine/10),-0.5+0*math["cos"](sine/10))*CFrame.Angles(math.rad(53.98+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)

elseif Root.Velocity.Magnitude > 20 then -- run
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(28.51+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(110.02+0*math.cos(sine/10)),math.rad(23.42+0*math.cos(sine/10)),math.rad(-32.62+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(110.02+0*math.cos(sine/10)),math.rad(-23.42+0*math.cos(sine/10)),math.rad(32.62+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0.6*math.cos(sine/10),0+0.5*math.cos(sine/10))*CFrame.Angles(math.rad(0+79.46*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.6*math.cos(sine/10),0+-0.5*math.cos(sine/10))*CFrame.Angles(math.rad(0+-79.46*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Back Bike','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),1.8+0*math["cos"](sine/10),-0.86+0*math["cos"](sine/10))*CFrame.Angles(math.rad(0+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+-2.06*math["cos"](sine/10))),false)

elseif Root.Velocity.Magnitude < 20 then -- walk
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0.57+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-32.62+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-33.6+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.14+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(125.31+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(33.6+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Back Bike','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),2+0*math["cos"](sine/10),-0.5+0*math["cos"](sine/10))*CFrame.Angles(math.rad(53.98+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)

end

elseif Mode == 'Attack1' then --attack clerp 
--none
elseif Mode == 'Attack2' then --attack clerp 
--none
elseif Mode == 'Attack3' then --attack clerp 
--none
end
srv.RenderStepped:Wait()
end
end)()
end)
local Section = Tab:NewSection("Gun Mafiahardyai")
Section:NewButton("Execute", "ButtonInfo", function()
    --hat needed: www.roblox.com/catalog/6774065728/DB12-Left-Hip

clickfling = true -- set this to false if u dont want click fling or use torso fling

function rmesh(a)
if not (workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('Mesh') or workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('SpecialMesh')) then return end
old=game.Players.LocalPlayer.Character
game.Players.LocalPlayer.Character=workspace[game.Players.LocalPlayer.Name]
for i,v in next, workspace[game.Players.LocalPlayer.Name]:FindFirstChild(a).Handle:GetDescendants() do
if v:IsA('Mesh') or v:IsA('SpecialMesh') then
v:Remove()
end
end
for i = 1 , 2 do
game.Players.LocalPlayer.Character=old
end
end

a=game.Players.LocalPlayer b=game.Players.LocalPlayer.Character c={}d=table.insert e=false for D,E in next,game:GetService("Players").LocalPlayer.Character:GetDescendants()do if E:IsA("BasePart")then d(c,game:GetService("RunService").Heartbeat:connect(function()pcall(function()E.Velocity=Vector3.new(-30,0,0)sethiddenproperty(game.Players.LocalPlayer,"MaximumSimulationRadius",math.huge)sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",999999999)game.Players.LocalPlayer.ReplicationFocus=workspace end)end))end end function f(D,E,F)game.StarterGui:SetCore("SendNotification",{Title=D;Text=E;Duration=F or 5;})end local x=game:GetService("RunService")g=Instance.new('Folder',b)g.Name='CWExtra'b.Archivable=true local y=b:Clone()y.Name='NexoPD'for D,E in next,y:GetDescendants()do if E:IsA('BasePart')or E:IsA('Decal')then E.Transparency=1 end end h=5.65 a.Character=nil a.Character=b b.Humanoid.AutoRotate=false b.Humanoid.WalkSpeed=0 b.Humanoid.JumpPower=0 b.Torso.Anchored=true f('DB Shotgun','Loading...\nPlease wait '..h..' seconds.')wait(h)b.Torso.Anchored=false f('DB Shotgun','Loaded..')b.Humanoid.Health=0 y.Animate.Disabled=true y.Parent=g y.HumanoidRootPart.CFrame=b.HumanoidRootPart.CFrame*CFrame.new(0,5,0)function i(D,E,F,G)Instance.new("Attachment",D)Instance.new("AlignPosition",D)Instance.new("AlignOrientation",D)Instance.new("Attachment",E)D.Attachment.Name=D.Name E.Attachment.Name=D.Name D.AlignPosition.Attachment0=D[D.Name]D.AlignOrientation.Attachment0=D[D.Name]D.AlignPosition.Attachment1=E[D.Name]D.AlignOrientation.Attachment1=E[D.Name]E[D.Name].Position=F or Vector3.new()D[D.Name].Orientation=G or Vector3.new()D.AlignPosition.MaxForce=999999999 D.AlignPosition.MaxVelocity=math.huge D.AlignPosition.ReactionForceEnabled=false D.AlignPosition.Responsiveness=math.huge D.AlignOrientation.Responsiveness=math.huge D.AlignPosition.RigidityEnabled=false D.AlignOrientation.MaxTorque=999999999 D.Massless=true end function j(D,E,F)Instance.new("Attachment",D)Instance.new("AlignPosition",D)Instance.new("Attachment",E)D.Attachment.Name=D.Name E.Attachment.Name=D.Name D.AlignPosition.Attachment0=D[D.Name]D.AlignPosition.Attachment1=E[D.Name]E[D.Name].Position=F or Vector3.new()D.AlignPosition.MaxForce=999999999 D.AlignPosition.MaxVelocity=math.huge D.AlignPosition.ReactionForceEnabled=false D.AlignPosition.Responsiveness=math.huge D.Massless=true end for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then d(c,x.RenderStepped:Connect(function()E.CanCollide=false end))end end for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then d(c,x.Stepped:Connect(function()E.CanCollide=false end))end end for D,E in next,y:GetDescendants()do if E:IsA('BasePart')then d(c,x.RenderStepped:Connect(function()E.CanCollide=false end))end end for D,E in next,y:GetDescendants()do if E:IsA('BasePart')then d(c,x.Stepped:Connect(function()E.CanCollide=false end))end end for D,E in next,b:GetDescendants()do if E:IsA('Accessory')then i(E.Handle,y[E.Name].Handle)end end i(b['Head'],y['Head'])i(b['Torso'],y['Torso'])j(b['HumanoidRootPart'],y['Torso'],Vector3.new(0,0,0))i(b['Right Arm'],y['Right Arm'])i(b['Left Arm'],y['Left Arm'])i(b['Right Leg'],y['Right Leg'])i(b['Left Leg'],y['Left Leg'])k=a:GetMouse()local z=Instance.new("Part",g)z.CanCollide=false z.Transparency=1 d(c,x.RenderStepped:Connect(function()local D=workspace.CurrentCamera.CFrame.lookVector local E=y["HumanoidRootPart"]z.Position=E.Position z.CFrame=CFrame.new(z.Position,Vector3.new(D.X*10000,D.Y,D.Z*10000))end))l=false m=false n=false o=false p=false function q(D)r=Instance.new('BodyAngularVelocity',D)r.AngularVelocity=Vector3.new(9e9,9e9,9e9)r.MaxTorque=Vector3.new(9e9,9e9,9e9)end q(b.HumanoidRootPart)k=a:GetMouse()s=Instance.new('BodyPosition',b.HumanoidRootPart)s.P=9e9 s.D=9e9 s.MaxForce=Vector3.new(99999,99999,99999)local A d(c,x.Heartbeat:Connect(function()if A==true then s.Position=k.Hit.p b.HumanoidRootPart.Position=k.Hit.p else s.Position=y.Torso.Position b.HumanoidRootPart.Position=y.Torso.Position end end))local B=Instance.new("SelectionBox")B.Adornee=b.HumanoidRootPart B.LineThickness=0.02 B.Color3=Color3.fromRGB(250,0,0)B.Parent=b.HumanoidRootPart B.Name="RAINBOW"t=B if clickfling then d(c,k.Button1Down:Connect(function()A=true end))d(c,k.Button1Up:Connect(function()A=false end))end d(c,k.KeyDown:Connect(function(D)if D==' 'then p=true end if D=='w'then l=true end if D=='s'then m=true end if D=='a'then n=true end if D=='d'then o=true end end))d(c,k.KeyUp:Connect(function(D)if D==' 'then p=false end if D=='w'then l=false end if D=='s'then m=false end if D=='a'then n=false end if D=='d'then o=false end end))local function C(D,E,F)z.CFrame=z.CFrame*CFrame.new(-D,E,-F)y.Humanoid.WalkToPoint=z.Position end d(c,x.RenderStepped:Connect(function()if l==true then C(0,0,1e4)end if m==true then C(0,0,-1e4)end if n==true then C(1e4,0,0)end if o==true then C(-1e4,0,0)end if p==true then y.Humanoid.Jump=true end if l~=true and n~=true and m~=true and o~=true then y.Humanoid.WalkToPoint=y.HumanoidRootPart.Position end end))workspace.CurrentCamera.CameraSubject=y.Humanoid u=Instance.new('BindableEvent')d(c,u.Event:Connect(function()y:Destroy()e=true v=false for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then E.Anchored=true end end w=b.Humanoid:Clone()b.Humanoid:Destroy()w.Parent=b game.Players:Chat('-re')for D,E in pairs(c)do E:Disconnect()end game:GetService("StarterGui"):SetCore("ResetButtonCallback",true)u:Remove()end))game:GetService("StarterGui"):SetCore("ResetButtonCallback",u)

IT = Instance.new
CF = CFrame.new
VT = Vector3.new
RAD = math.rad
C3 = Color3.new
UD2 = UDim2.new
BRICKC = BrickColor.new
ANGLES = CFrame.Angles
EULER = CFrame.fromEulerAnglesXYZ
COS = math.cos
ACOS = math.acos
SIN = math.sin
ASIN = math.asin
ABS = math.abs
MRANDOM = math.random
FLOOR = math.floor

speed = 1
sine = 1
srv = game:GetService('RunService')

reanim = workspace.Camera.CameraSubject.Parent

function hat(h,p,c1,c0,m)
reanim[h].Handle.AccessoryWeld.Part1=reanim[p]
reanim[h].Handle.AccessoryWeld.C1=c1 or CFrame.new()
reanim[h].Handle.AccessoryWeld.C0=reanim[h].Handle.AccessoryWeld.C0:Lerp(c0 or CFrame.new(),1)
if m == true then
rmesh(h)
end
end

m=game.Players.LocalPlayer:GetMouse()
RJ = reanim.HumanoidRootPart.RootJoint
RS = reanim.Torso['Right Shoulder']
LS = reanim.Torso['Left Shoulder']
RH = reanim.Torso['Right Hip']
LH = reanim.Torso['Left Hip']
Root = reanim.HumanoidRootPart
NECK = reanim.Torso.Neck
NECK.C0 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
NECK.C1 = CF(0,-0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C1 = CF(0,-1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))

Mode='2'
reanim.Humanoid.WalkSpeed = 16
mousechanger=game.Players.LocalPlayer:GetMouse().KeyDown:Connect(function(k)
if k == 'e' then-- first mode
Mode='1'
reanim.Humanoid.WalkSpeed = 16
elseif k == 'q' then-- second mode
Mode='2'
end
end)

attacklol=game.Players.LocalPlayer:GetMouse().Button1Down:Connect(function()
Mode='Attack1'
wait(0.45) -- time of attack u can edit this
Mode='Attack2'
wait(0)
Mode='Attack3'
wait(0)
Mode ='2' -- change this mode to whatever u want the mode to be after attacking
end)
hat('Meshes/DB12Accessory','Right Arm',CFrame.new(0,0,0),CFrame.new(-0.25+0*math["cos"](sine/10),-0.4+0*math["cos"](sine/10),-1.22+0*math["cos"](sine/10))*CFrame.Angles(math.rad(90+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10))),false)
coroutine.wrap(function()
while true do -- anim changer
if HumanDied then break end
sine = sine + speed
local rlegray = Ray.new(reanim["Right Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local rlegpart, rlegendPoint = workspace:FindPartOnRay(rlegray, char)
local llegray = Ray.new(reanim["Left Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local llegpart, llegendPoint = workspace:FindPartOnRay(llegray, char)
local rightvector = (Root.Velocity * Root.CFrame.rightVector).X + (Root.Velocity * Root.CFrame.rightVector).Z
local lookvector = (Root.Velocity * Root.CFrame.lookVector).X + (Root.Velocity * Root.CFrame.lookVector).Z
if lookvector > reanim.Humanoid.WalkSpeed then
lookvector = reanim.Humanoid.WalkSpeed
end
if lookvector < -reanim.Humanoid.WalkSpeed then
lookvector = -reanim.Humanoid.WalkSpeed
end
if rightvector > reanim.Humanoid.WalkSpeed then
rightvector = reanim.Humanoid.WalkSpeed
end
if rightvector < -reanim.Humanoid.WalkSpeed then
rightvector = -reanim.Humanoid.WalkSpeed
end
local lookvel = lookvector / reanim.Humanoid.WalkSpeed
local rightvel = rightvector / reanim.Humanoid.WalkSpeed
if Mode == '1' then

if Root.Velocity.y > 1 then -- jump
hat('Meshes/DB12Accessory','Torso',CFrame.new(0,0,0),CFrame.new(1+0*math["cos"](sine/10),0+0*math["cos"](sine/10),-1+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-90+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-9.7+2*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(35+45*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-35+-45*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Root.Velocity.y < -1 then -- fall
hat('Meshes/DB12Accessory','Torso',CFrame.new(0,0,0),CFrame.new(1+0*math["cos"](sine/10),0+0*math["cos"](sine/10),-1+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-90+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-9.7+2*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(35+45*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-35+-45*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude < 2 then -- idle
hat('Meshes/DB12Accessory','Torso',CFrame.new(0,0,0),CFrame.new(1+0*math["cos"](sine/10),0+0*math["cos"](sine/10),-1+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-90+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.1*math.sin(sine/30),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(5+5*math.cos(sine/30)),math.rad(0+0*math.cos(sine/30)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1+0*math.cos(sine/10),0.3+0.1*math.sin(sine/30),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(-40.27+0*math.cos(sine/10)),math.rad(-24.98+0*math.cos(sine/10)),math.rad(-86.12+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1+0*math.cos(sine/10),0.3+0.1*math.sin(sine/30),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(28.51+0*math.cos(sine/10)),math.rad(13.23+0*math.cos(sine/10)),math.rad(82+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.1*math.sin(sine/30),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-5+-5*math.cos(sine/30)),math.rad(-20+0*math.cos(sine/10)),math.rad(5+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.1*math.sin(sine/30),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-5+-5*math.cos(sine/30)),math.rad(25+0*math.cos(sine/10)),math.rad(-5+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude > 20 then -- run

elseif Root.Velocity.Magnitude < 20 then -- walk
hat('Meshes/DB12Accessory','Torso',CFrame.new(0,0,0),CFrame.new(1+0*math["cos"](sine/10),0+0*math["cos"](sine/10),-1+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-90+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+-0.1*math.sin(sine/7.5),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-15+5*math.cos(sine/7.5)),math.rad(0+10*math.cos(sine/15)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.sin(sine/15),0+0*math.cos(sine/15))*CFrame.Angles(math.rad(0+-60*math.cos(sine/15)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.sin(sine/30),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+60*math.cos(sine/15)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/15),-1+-0.2*math.sin(sine/15),0+-0.5*math.cos(sine/15))*CFrame.Angles(math.rad(10+50*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0.2*math.sin(sine/15),0+0.5*math.cos(sine/15))*CFrame.Angles(math.rad(10+-50*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2)
end

elseif Mode == '2' then
reanim.Humanoid.WalkSpeed = 16
if Root.Velocity.y > 1 then -- jump
hat('Meshes/DB12Accessory','Right Arm',CFrame.new(0,0,0),CFrame.new(-0.25+0*math["cos"](sine/10),-0.4+0*math["cos"](sine/10),-1.22+0*math["cos"](sine/10))*CFrame.Angles(math.rad(90+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-9.7+2*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(35+45*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-35+-45*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Root.Velocity.y < -1 then -- fall
hat('Meshes/DB12Accessory','Right Arm',CFrame.new(0,0,0),CFrame.new(-0.25+0*math["cos"](sine/10),-0.4+0*math["cos"](sine/10),-1.22+0*math["cos"](sine/10))*CFrame.Angles(math.rad(90+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-9.7+2*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(35+45*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-35+-45*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude < 2 then -- idle
hat('Meshes/DB12Accessory','Right Arm',CFrame.new(0,0,0),CFrame.new(-0.25+0*math["cos"](sine/10),-0.4+0*math["cos"](sine/10),-1.22+0*math["cos"](sine/10))*CFrame.Angles(math.rad(90+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.05*math.sin(sine/30),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(0.75+0*math.cos(sine/10),-0.25+0.05*math.cos(sine/30),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(181.35+0*math.cos(sine/10)),math.rad(-70.83+10*math.cos(sine/30)),math.rad(20.87+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.05*math.cos(sine/30),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(20+0*math.cos(sine/30)),math.rad(35+0*math.cos(sine/10)),math.rad(-20+5*math.cos(sine/30))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.05*math.sin(sine/30),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-20+0*math.cos(sine/10)),math.rad(10+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.05*math.sin(sine/30),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(20+0*math.cos(sine/10)),math.rad(-10+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude > 20 then -- run

elseif Root.Velocity.Magnitude < 20 then -- walk
hat('Meshes/DB12Accessory','Right Arm',CFrame.new(0,0,0),CFrame.new(-0.25+0*math["cos"](sine/10),-0.4+0*math["cos"](sine/10),-1.22+0*math["cos"](sine/10))*CFrame.Angles(math.rad(90+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.1*math.sin(sine/7.5),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-10+0*math.cos(sine/10)),math.rad(0+10*math.cos(sine/15)),math.rad(0+5*math.cos(sine/15))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(0.75+0*math.cos(sine/10),-0.25+0.1*math.cos(sine/15),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(181.35+0*math.cos(sine/10)),math.rad(-70.83+10*math.cos(sine/30)),math.rad(20.87+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/7.5),0.5+0.1*math.cos(sine/7.5),0+0.2*math.cos(sine/7.5))*CFrame.Angles(math.rad(0+50*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/15),-1+-0.2*math.sin(sine/15),0+-0.4*math.cos(sine/15))*CFrame.Angles(math.rad(0+60*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/15),-1+0.2*math.sin(sine/15),0+0.4*math.cos(sine/15))*CFrame.Angles(math.rad(0+-60*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2)
end

elseif Mode == 'Attack1' then --attack clerp 
hat('Meshes/DB12Accessory','Right Arm',CFrame.new(0,0,0),CFrame.new(-0.25+0*math["cos"](sine/10),-0.4+0*math["cos"](sine/10),-1.22+0*math["cos"](sine/10))*CFrame.Angles(math.rad(90+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(180+0*math["cos"](sine/10))),false)
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-9.7+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.1*math.sin(sine/20),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/5),0.39+0*math.cos(sine/5),-0.5+0*math.cos(sine/5))*CFrame.Angles(math.rad(95+5*math.cos(sine/5)),math.rad(0+0*math.cos(sine/5)),math.rad(0+0*math.cos(sine/5))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-0.4+0*math.cos(sine/5),-1.29+-0.1*math.cos(sine/5))*CFrame.Angles(math.rad(125+5*math.cos(sine/5)),math.rad(20.87+0*math.cos(sine/10)),math.rad(28.51+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.1*math.sin(sine/20),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-20+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.1*math.sin(sine/20),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(20+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Mode == 'Attack2' then --attack clerp 
RS.C0=RS.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/5),0.39+0*math.cos(sine/5),-0.5+0*math.cos(sine/5))*CFrame.Angles(math.rad(90+0*math.cos(sine/5)),math.rad(0+0*math.cos(sine/5)),math.rad(0+0*math.cos(sine/5))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-0.4+0*math.cos(sine/5),-1.29+0*math.cos(sine/5))*CFrame.Angles(math.rad(120+0*math.cos(sine/5)),math.rad(20.87+0*math.cos(sine/10)),math.rad(28.51+0*math.cos(sine/10))),.2) 
elseif Mode == 'Attack3' then --attack clerp 
RS.C0=RS.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/5),0.39+0*math.cos(sine/5),-0.5+0*math.cos(sine/5))*CFrame.Angles(math.rad(90+0*math.cos(sine/5)),math.rad(0+0*math.cos(sine/5)),math.rad(0+0*math.cos(sine/5))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-0.4+0*math.cos(sine/5),-1.29+0*math.cos(sine/5))*CFrame.Angles(math.rad(120+0*math.cos(sine/5)),math.rad(20.87+0*math.cos(sine/10)),math.rad(28.51+0*math.cos(sine/10))),.2) 
end
srv.RenderStepped:Wait()
end
end)()
end)

local Tab = Window:NewTab("Bookhaven")
local Section = Tab:NewSection("Chat Fake")
Section:NewButton("Execute", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/ant-7802/--/main/straightmilk.lua'))()
end)
local Section = Tab:NewSection("infiniteyield admin menu")
Section:NewButton("Execute", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
local Section = Tab:NewSection("Icehub")
Section:NewButton("Execute", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
end)

local Tab = Window:NewTab("Bild a Boat")
local Section = Tab:NewSection("Vynixius HUB")
Section:NewButton("Eexcute", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Build%20A%20Boat%20For%20Treasure/BABFT"))()
end)


local Tab = Window:NewTab("Kram Life")
local Section = Tab:NewSection("Project X HUB")
Section:NewButton("Execute", "ButtonInfo", function()
    -- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Kerry = Instance.new("TextButton")
local animalHunter = Instance.new("TextButton")
local Cafe = Instance.new("TextButton")
local clinics = Instance.new("TextButton")
local Hotel = Instance.new("TextButton")
local MetalBookshop = Instance.new("TextButton")
local Mine = Instance.new("TextButton")
local Ptt = Instance.new("TextButton")
local Rice = Instance.new("TextButton")
local TechincShop = Instance.new("TextButton")
local woodcut = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(0.67478919, 0, 0.565392315, 0)
Frame.Size = UDim2.new(0, 339, 0, 207)

Kerry.Name = "Kerry"
Kerry.Parent = Frame
Kerry.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Kerry.Position = UDim2.new(0.0707964897, 0, 0.144927531, 0)
Kerry.Size = UDim2.new(0, 68, 0, 19)
Kerry.Font = Enum.Font.SourceSans
Kerry.Text = "Kerry"
Kerry.TextColor3 = Color3.fromRGB(0, 0, 0)
Kerry.TextSize = 14.000
Kerry.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (-17.1097336, 42.0181999, -210.133713, 0.203991294, -5.94625362e-08, 0.978972673, 6.38493844e-08, 1, 4.74352539e-08, -0.978972673, 5.28304227e-08, 0.203991294)
end)

animalHunter.Name = "animal Hunter"
animalHunter.Parent = Frame
animalHunter.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
animalHunter.Position = UDim2.new(0.0707964897, 0, 0.32367149, 0)
animalHunter.Size = UDim2.new(0, 68, 0, 19)
animalHunter.Font = Enum.Font.SourceSans
animalHunter.Text = "animal Hunter"
animalHunter.TextColor3 = Color3.fromRGB(0, 0, 0)
animalHunter.TextSize = 14.000
animalHunter.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (-916.731506, 35.5928535, 625.346069, -0.120072037, 4.18972101e-09, -0.992765188, -1.16068994e-08, 1, 5.6240741e-09, 0.992765188, 1.21982193e-08, -0.120072037)
end)

Cafe.Name = "Cafe"
Cafe.Parent = Frame
Cafe.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Cafe.Position = UDim2.new(0.0707964897, 0, 0.516908228, 0)
Cafe.Size = UDim2.new(0, 68, 0, 19)
Cafe.Font = Enum.Font.SourceSans
Cafe.Text = "Cafe"
Cafe.TextColor3 = Color3.fromRGB(0, 0, 0)
Cafe.TextSize = 14.000
Cafe.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (-600.664185, 115.516457, 30.2758961, 0.0726496503, 4.53961633e-08, -0.997357547, -4.07329814e-08, 1, 4.25493631e-08, 0.997357547, 3.75341465e-08, 0.0726496503)
end)

clinics.Name = "clinics"
clinics.Parent = Frame
clinics.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
clinics.Position = UDim2.new(0.0707964897, 0, 0.710144937, 0)
clinics.Size = UDim2.new(0, 68, 0, 19)
clinics.Font = Enum.Font.SourceSans
clinics.Text = "clinics"
clinics.TextColor3 = Color3.fromRGB(0, 0, 0)
clinics.TextSize = 14.000
clinics.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (16.5457039, 26.1295757, 615.36084, -0.981516302, -1.76247905e-08, 0.191378623, -7.22807592e-09, 1, 5.50234738e-08, -0.191378623, 5.26231361e-08, -0.981516302)
end)

Hotel.Name = "Hotel"
Hotel.Parent = Frame
Hotel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hotel.Position = UDim2.new(0.324483812, 0, 0.710144937, 0)
Hotel.Size = UDim2.new(0, 68, 0, 19)
Hotel.Font = Enum.Font.SourceSans
Hotel.Text = "Hotel"
Hotel.TextColor3 = Color3.fromRGB(0, 0, 0)
Hotel.TextSize = 14.000
Hotel.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (-45.0985336, 29.2248363, 179.440018, 0.337209851, -3.14741087e-08, 0.941429496, 4.43711112e-09, 1, 3.18429265e-08, -0.941429496, -6.56052102e-09, 0.337209851)
end)

MetalBookshop.Name = "Metal Book shop"
MetalBookshop.Parent = Frame
MetalBookshop.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MetalBookshop.Position = UDim2.new(0.324483812, 0, 0.516908228, 0)
MetalBookshop.Size = UDim2.new(0, 68, 0, 19)
MetalBookshop.Font = Enum.Font.SourceSans
MetalBookshop.Text = "Metal Book "
MetalBookshop.TextColor3 = Color3.fromRGB(0, 0, 0)
MetalBookshop.TextSize = 14.000
MetalBookshop.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (-83.5617447, 25.4097023, 581.82074, 0.0518463887, 6.69749456e-09, -0.998655081, -2.86795458e-08, 1, 5.21758103e-09, 0.998655081, 2.83704615e-08, 0.0518463887)
end)

Mine.Name = "Mine"
Mine.Parent = Frame
Mine.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Mine.Position = UDim2.new(0.324483812, 0, 0.144927531, 0)
Mine.Size = UDim2.new(0, 68, 0, 19)
Mine.Font = Enum.Font.SourceSans
Mine.Text = "Mine"
Mine.TextColor3 = Color3.fromRGB(0, 0, 0)
Mine.TextSize = 14.000
Mine.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (-376.482056, 27.3877773, 214.249939, 0.800624788, 6.84749324e-08, 0.599166036, -2.41565772e-08, 1, -8.2004938e-08, -0.599166036, 5.1181388e-08, 0.800624788)
end)

Ptt.Name = "Ptt"
Ptt.Parent = Frame
Ptt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Ptt.Position = UDim2.new(0.324483812, 0, 0.32367149, 0)
Ptt.Size = UDim2.new(0, 68, 0, 19)
Ptt.Font = Enum.Font.SourceSans
Ptt.Text = "Ptt"
Ptt.TextColor3 = Color3.fromRGB(0, 0, 0)
Ptt.TextSize = 14.000
Ptt.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (70.8248291, 29.6235733, 219.079453, 0.9682585, -9.19189702e-08, -0.24995099, 7.95340327e-08, 1, -5.96495795e-08, 0.24995099, 3.78766032e-08, 0.9682585)
end)

Rice.Name = "Rice"
Rice.Parent = Frame
Rice.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Rice.Position = UDim2.new(0.572271407, 0, 0.144927531, 0)
Rice.Size = UDim2.new(0, 68, 0, 19)
Rice.Font = Enum.Font.SourceSans
Rice.Text = "Rice"
Rice.TextColor3 = Color3.fromRGB(0, 0, 0)
Rice.TextSize = 14.000
Rice.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (-337.193451, 68.2686615, -676.516235, 0.927302361, -8.57545768e-09, 0.374313176, -2.87619688e-08, 1, 9.41631271e-08, -0.374313176, -9.80836745e-08, 0.927302361)
end)

TechincShop.Name = "Techinc Shop"
TechincShop.Parent = Frame
TechincShop.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TechincShop.Position = UDim2.new(0.572271407, 0, 0.32367149, 0)
TechincShop.Size = UDim2.new(0, 68, 0, 19)
TechincShop.Font = Enum.Font.SourceSans
TechincShop.Text = "Techinc Shop"
TechincShop.TextColor3 = Color3.fromRGB(0, 0, 0)
TechincShop.TextSize = 14.000
TechincShop.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (-11.3105822, 26.1294441, 692.149719, 0.821799159, -4.52424764e-08, 0.56977731, -1.26666171e-08, 1, 9.7673059e-08, -0.56977731, -8.74847927e-08, 0.821799159)
end)

woodcut.Name = "wood cut"
woodcut.Parent = Frame
woodcut.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
woodcut.Position = UDim2.new(0.572271407, 0, 0.516908169, 0)
woodcut.Size = UDim2.new(0, 68, 0, 19)
woodcut.Font = Enum.Font.SourceSans
woodcut.Text = "wood cut"
woodcut.TextColor3 = Color3.fromRGB(0, 0, 0)
woodcut.TextSize = 14.000
woodcut.MouseButton1Down:Connect(function()
	game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new (-40.5229912, 32.309288, -704.934143, 0.614596546, 2.65387854e-08, 0.788841605, 4.02462987e-08, 1, -6.4999135e-08, -0.788841605, 7.16961992e-08, 0.614596546)
end)
end)

local Tab = Window:NewTab("Murder Mystery 2")
local Section = Tab:NewSection("Eclipse hub")
Section:NewButton("Execute", "ButtonInfo", function()
    getgenv().mainKey = "nil" local a,b,c,d,e=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,tostring,"https://api.eclipsehub.xyz/auth"c(a and b,"Executor not Supported")a(b({Url=e.."\?\107e\121\61"..d(mainKey),Headers={["User-Agent"]="Eclipse"}}).Body)()
end)

local Tab = Window:NewTab("Da Hood")
local Section = Tab:NewSection("ARCTIC Hub")
Section:NewButton("Execute", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/spacexrandom/Lua/main/DaHood", true))()
end)
local Section = Tab:NewSection("VALIANT Hub")
Section:NewButton("Execute", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/cypherdh/Valiant/main/script"))()
end)
local Section = Tab:NewSection("DESTINY Hub")
Section:NewButton("Execute", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/compwnter/destiny/main/loader'))();
end)

local Tab = Window:NewTab("SharkBite")
local Section = Tab:NewSection("No name Hub")
Section:NewButton("Execute", "ButtonInfo", function()
    getgenv().http_request = http_request or request or (http and http.request) or syn.request 
repeat until http_request
loadstring(http_request({Url="https://raw.githubusercontent.com/alphaalt0409/WEIRDAPPLEBEEPANEL/main/weirdapplebee.lua",Method="GET"}).Body)()
end)
