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

local Section = Tab:NewSection("Cat Kick")
Section:NewButton("Execute", "ButtonInfo", function()
    --BROUGHT TO YOU BY RSCRIPTS.NET--

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

-- for modes u can go in this link : https://Nexo.notxeneon15.repl.co/nexo/modes.lua

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
if reanim.Humanoid.Jump then -- jump
--jump clerp here
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(75+10*math.cos(sine/4)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/22.25),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-63.19+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(166+25*math.cos(sine/10)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2)
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(166+-25*math.cos(sine/10)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2)
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(60+15*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(10+0*math.cos(sine/10))),.2)
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(60+-15*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-10+0*math.cos(sine/10))),.2)
elseif Root.Velocity.y < -1 and reanim.Humanoid.Jump then -- fall
--fall clerp here
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(75+10*math.cos(sine/4)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/22.25),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-109.04+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(166+25*math.cos(sine/10)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2)
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(166+-25*math.cos(sine/10)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2)
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(60+15*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(10+0*math.cos(sine/10))),.2)
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(60+-15*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-10+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude < 2 then -- idle
--idle clerp here
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(21+-2*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-3+0.02*math.cos(sine/22.25),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+5.5*math.cos(sine/15)),math.rad(25+1*math.cos(sine/15))),.2)
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+-5.5*math.cos(sine/15)),math.rad(-25+1*math.cos(sine/15))),.2)
RH.C0=RH.C0:Lerp(CFrame.new(1+0*math.cos(sine/10),0.3+0*math.cos(sine/10),-0.3+0*math.cos(sine/10))*CFrame.Angles(math.rad(28+0*math.cos(sine/10)),math.rad(0+-2*math.cos(sine/10)),math.rad(-13+2*math.cos(sine/10))),.2)
LH.C0=LH.C0:Lerp(CFrame.new(-1+0*math.cos(sine/10),0.3+0*math.cos(sine/10),-0.3+0*math.cos(sine/10))*CFrame.Angles(math.rad(28+0*math.cos(sine/10)),math.rad(0+2*math.cos(sine/10)),math.rad(13+-2*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude < 20 then -- walk
--walk clerp here
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(50+5.58*math.cos(sine/10)),math.rad(0+10*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/22.25),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-90+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(90+27*math.cos(sine/10)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2)
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(90+-27*math.cos(sine/10)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15))),.2)
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(90+-27*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(90+27*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude > 20 then -- run
--run clerp here
end
srv.RenderStepped:Wait()
end
end)()
end)
local Section = Tab:NewSection("Move Tool")
Section:NewButton("Execute", "ButtonInfo", function()
    function sandbox(var,func)
		local env = getfenv(func)
		local newenv = setmetatable({},{
			__index = function(self,k)
				if k=="script" then
					return var
				else
					return env[k]
				end
			end,
		})
		setfenv(func,newenv)
		return func
	end
	cors = {}
	mas = Instance.new("Model",game:GetService("Lighting"))
	Tool0 = Instance.new("Tool")
	Part1 = Instance.new("Part")
	CylinderMesh2 = Instance.new("CylinderMesh")
	Part3 = Instance.new("Part")
	LocalScript4 = Instance.new("LocalScript")
	Script5 = Instance.new("Script")
	LocalScript6 = Instance.new("LocalScript")
	Script7 = Instance.new("Script")
	LocalScript8 = Instance.new("LocalScript")
	Part9 = Instance.new("Part")
	Script10 = Instance.new("Script")
	Part11 = Instance.new("Part")
	Script12 = Instance.new("Script")
	Part13 = Instance.new("Part")
	Script14 = Instance.new("Script")
	Tool0.Name = "Telekinesis Gun"
	Tool0.Parent = mas
	Tool0.CanBeDropped = false
	Part1.Name = "Handle"
	Part1.Parent = Tool0
	Part1.Material = Enum.Material.Neon
	Part1.BrickColor = BrickColor.new("Cyan")
	Part1.Transparency = 1
	Part1.Rotation = Vector3.new(0, 15.4200001, 0)
	Part1.CanCollide = false
	Part1.FormFactor = Enum.FormFactor.Custom
	Part1.Size = Vector3.new(1, 0.400000036, 0.300000012)
	Part1.CFrame = CFrame.new(-55.2695465, 0.696546972, 0.383156985, 0.96399641, -4.98074878e-05, 0.265921414, 4.79998416e-05, 1, 1.32960558e-05, -0.265921414, -5.30653779e-08, 0.96399641)
	Part1.BottomSurface = Enum.SurfaceType.Smooth
	Part1.TopSurface = Enum.SurfaceType.Smooth
	Part1.Color = Color3.new(0.0156863, 0.686275, 0.92549)
	Part1.Position = Vector3.new(-55.2695465, 0.696546972, 0.383156985)
	Part1.Orientation = Vector3.new(0, 15.4200001, 0)
	Part1.Color = Color3.new(0.0156863, 0.686275, 0.92549)
	CylinderMesh2.Parent = Part1
	CylinderMesh2.Scale = Vector3.new(0.100000001, 0.100000001, 0.100000001)
	CylinderMesh2.Scale = Vector3.new(0.100000001, 0.100000001, 0.100000001)
	Part3.Name = "Shoot"
	Part3.Parent = Tool0
	Part3.Material = Enum.Material.Neon
	Part3.BrickColor = BrickColor.new("Cyan")
	Part3.Reflectance = 0.30000001192093
	Part3.Transparency = 1
	Part3.Rotation = Vector3.new(90.9799957, 0.25999999, -91.409996)
	Part3.CanCollide = false
	Part3.FormFactor = Enum.FormFactor.Custom
	Part3.Size = Vector3.new(0.200000003, 0.25, 0.310000032)
	Part3.CFrame = CFrame.new(-54.7998123, 0.774299085, -0.757350147, -0.0245519895, 0.99968797, 0.00460194098, 0.0169109926, 0.00501798885, -0.999844491, -0.999555528, -0.0244703442, -0.0170289185)
	Part3.BottomSurface = Enum.SurfaceType.Smooth
	Part3.TopSurface = Enum.SurfaceType.Smooth
	Part3.Color = Color3.new(0.0156863, 0.686275, 0.92549)
	Part3.Position = Vector3.new(-54.7998123, 0.774299085, -0.757350147)
	Part3.Orientation = Vector3.new(88.9899979, 164.87999, 73.4700012)
	Part3.Color = Color3.new(0.0156863, 0.686275, 0.92549)
	LocalScript4.Parent = Tool0
	table.insert(cors,sandbox(LocalScript4,function()
	-- Variables for services
	local render = game:GetService("RunService").RenderStepped
	local contextActionService = game:GetService("ContextActionService")
	local userInputService = game:GetService("UserInputService")
	
	local player = game.Players.LocalPlayer
	local mouse = player:GetMouse()
	local Tool = script.Parent
	
	-- Variables for Module Scripts
	local screenSpace = require(Tool:WaitForChild("ScreenSpace"))
	
	local connection
	-- Variables for character joints
	
	local neck, shoulder, oldNeckC0, oldShoulderC0 
	
	local mobileShouldTrack = true
	
	-- Thourough check to see if a character is sitting
	local function amISitting(character)
		local t = character.Torso
		for _, part in pairs(t:GetConnectedParts(true)) do
			if part:IsA("Seat") or part:IsA("VehicleSeat") then
				return true
			end
		end
	end
	
	-- Function to call on renderstepped. Orients the character so it is facing towards
	-- the player mouse's position in world space. If character is sitting then the torso
	-- should not track
	local function frame(mousePosition)
		-- Special mobile consideration. We don't want to track if the user was touching a ui
		-- element such as the movement controls. Just return out of function if so to make sure
		-- character doesn't track
		if not mobileShouldTrack then return end
		
		-- Make sure character isn't swiming. If the character is swimming the following code will
		-- not work well; the character will not swim correctly. Besides, who shoots underwater?
		if player.Character.Humanoid:GetState() ~= Enum.HumanoidStateType.Swimming then
			local torso = player.Character.Torso
			local head = player.Character.Head
			
			local toMouse = (mousePosition - head.Position).unit
			local angle = math.acos(toMouse:Dot(Vector3.new(0,1,0)))
			
			local neckAngle = angle
		
			-- Limit how much the head can tilt down. Too far and the head looks unnatural
			if math.deg(neckAngle) > 110 then
				neckAngle = math.rad(110)
			end
			neck.C0 = CFrame.new(0,1,0) * CFrame.Angles(math.pi - neckAngle,math.pi,0)
			
			-- Calculate horizontal rotation
			local arm = player.Character:FindFirstChild("Right Arm")
			local fromArmPos = torso.Position + torso.CFrame:vectorToWorldSpace(Vector3.new(
				torso.Size.X/2 + arm.Size.X/2, torso.Size.Y/2 - arm.Size.Z/2, 0))
			local toMouseArm = ((mousePosition - fromArmPos) * Vector3.new(1,0,1)).unit
			local look = (torso.CFrame.lookVector * Vector3.new(1,0,1)).unit
			local lateralAngle = math.acos(toMouseArm:Dot(look))		
			
			-- Check for rogue math
			if tostring(lateralAngle) == "-1.#IND" then
				lateralAngle = 0
			end		
			
			-- Handle case where character is sitting down
			if player.Character.Humanoid:GetState() == Enum.HumanoidStateType.Seated then			
				
				local cross = torso.CFrame.lookVector:Cross(toMouseArm)
				if lateralAngle > math.pi/2 then
					lateralAngle = math.pi/2
				end
				if cross.Y < 0 then
					lateralAngle = -lateralAngle
				end
			end	
			
			-- Turn shoulder to point to mouse
			shoulder.C0 = CFrame.new(1,0.5,0) * CFrame.Angles(math.pi/2 - angle,math.pi/2 + lateralAngle,0)	
			
			-- If not sitting then aim torso laterally towards mouse
			if not amISitting(player.Character) then
				torso.CFrame = CFrame.new(torso.Position, torso.Position + (Vector3.new(
					mousePosition.X, torso.Position.Y, mousePosition.Z)-torso.Position).unit)
			else
				--print("sitting")		
			end	
		end
	end
	
	-- Function to bind to render stepped if player is on PC
	local function pcFrame()
		frame(mouse.Hit.p)
	end
	
	-- Function to bind to touch moved if player is on mobile
	local function mobileFrame(touch, processed)
		-- Check to see if the touch was on a UI element. If so, we don't want to update anything
		if not processed then
			-- Calculate touch position in world space. Uses Stravant's ScreenSpace Module script
			-- to create a ray from the camera.
			local test = screenSpace.ScreenToWorld(touch.Position.X, touch.Position.Y, 1)
			local nearPos = game.Workspace.CurrentCamera.CoordinateFrame:vectorToWorldSpace(screenSpace.ScreenToWorld(touch.Position.X, touch.Position.Y, 1))
			nearPos = game.Workspace.CurrentCamera.CoordinateFrame.p - nearPos
			local farPos = screenSpace.ScreenToWorld(touch.Position.X, touch.Position.Y,50) 
			farPos = game.Workspace.CurrentCamera.CoordinateFrame:vectorToWorldSpace(farPos) * -1
			if farPos.magnitude > 900 then
				farPos = farPos.unit * 900
			end
			local ray = Ray.new(nearPos, farPos)
			local part, pos = game.Workspace:FindPartOnRay(ray, player.Character)
			
			-- if a position was found on the ray then update the character's rotation
			if pos then
				frame(pos)
			end
		end
	end
	
	local oldIcon = nil
	-- Function to bind to equip event
	local function equip()
		local torso = player.Character.Torso
		
		-- Setup joint variables
		neck = torso.Neck	
		oldNeckC0 = neck.C0
		shoulder = torso:FindFirstChild("Right Shoulder")
		oldShoulderC0 = shoulder.C0
		
		-- Remember old mouse icon and update current
		oldIcon = mouse.Icon
		mouse.Icon = "rbxassetid:// 2184939409"
		
		-- Bind TouchMoved event if on mobile. Otherwise connect to renderstepped
		if userInputService.TouchEnabled then
			connection = userInputService.TouchMoved:connect(mobileFrame)
		else
			connection = render:connect(pcFrame)
		end
		
		-- Bind TouchStarted and TouchEnded. Used to determine if character should rotate
		-- during touch input
		userInputService.TouchStarted:connect(function(touch, processed)
			mobileShouldTrack = not processed
		end)	
		userInputService.TouchEnded:connect(function(touch, processed)
			mobileShouldTrack = false
		end)
		
		-- Fire server's equip event
		game.ReplicatedStorage.ROBLOX_PistolEquipEvent:FireServer()
		
		-- Bind event for when mouse is clicked to fire server's fire event
		mouse.Button1Down:connect(function()
			game.ReplicatedStorage.ROBLOX_PistolFireEvent:FireServer(mouse.Hit.p)
		end)
		
		-- Bind reload event to mobile button and r key
		contextActionService:BindActionToInputTypes("Reload", function() 
			game.ReplicatedStorage.ROBLOX_PistolReloadEvent:FireServer()		
		end, true, "")
		
		-- If game uses filtering enabled then need to update server while tool is
		-- held by character.
		if workspace.FilteringEnabled then
			while connection do
				wait()
				game.ReplicatedStorage.ROBLOX_PistolUpdateEvent:FireServer(neck.C0, shoulder.C0)
			end
		end
	end
	
	-- Function to bind to Unequip event
	local function unequip()
		if connection then connection:disconnect() end
		contextActionService:UnbindAction("Reload")
		game.ReplicatedStorage.ROBLOX_PistolUnequipEvent:FireServer()
		mouse.Icon = oldIcon
		neck.C0 = oldNeckC0
		shoulder.C0 = oldShoulderC0
	end
	
	-- Bind tool events
	Tool.Equipped:connect(equip)
	Tool.Unequipped:connect(unequip)
	end))
	Script5.Name = "qPerfectionWeld"
	Script5.Parent = Tool0
	table.insert(cors,sandbox(Script5,function()
	-- Created by Quenty (@Quenty, follow me on twitter).
	-- Should work with only ONE copy, seamlessly with weapons, trains, et cetera.
	-- Parts should be ANCHORED before use. It will, however, store relatives values and so when tools are reparented, it'll fix them.
	
	--[[ INSTRUCTIONS
	- Place in the model
	- Make sure model is anchored
	- That's it. It will weld the model and all children. 
	
	THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
	THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
	THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
	THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
	THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
	THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
	THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
	THIS SCRIPT SHOULD BE USED ONLY BY ITSELF. THE MODEL SHOULD BE ANCHORED. 
	
	This script is designed to be used is a regular script. In a local script it will weld, but it will not attempt to handle ancestory changes. 
	]]
	
	--[[ DOCUMENTATION
	- Will work in tools. If ran more than once it will not create more than one weld.  This is especially useful for tools that are dropped and then picked up again.
	- Will work in PBS servers
	- Will work as long as it starts out with the part anchored
	- Stores the relative CFrame as a CFrame value
	- Takes careful measure to reduce lag by not having a joint set off or affected by the parts offset from origin
	- Utilizes a recursive algorith to find all parts in the model
	- Will reweld on script reparent if the script is initially parented to a tool.
	- Welds as fast as possible
	]]
	
	-- qPerfectionWeld.lua
	-- Created 10/6/2014
	-- Author: Quenty
	-- Version 1.0.3
	
	-- Updated 10/14/2014 - Updated to 1.0.1
	--- Bug fix with existing ROBLOX welds ? Repro by asimo3089
	
	-- Updated 10/14/2014 - Updated to 1.0.2
	--- Fixed bug fix. 
	
	-- Updated 10/14/2014 - Updated to 1.0.3
	--- Now handles joints semi-acceptably. May be rather hacky with some joints. :/
	
	local NEVER_BREAK_JOINTS = false -- If you set this to true it will never break joints (this can create some welding issues, but can save stuff like hinges).
	
	
	local function CallOnChildren(Instance, FunctionToCall)
		-- Calls a function on each of the children of a certain object, using recursion.  
	
		FunctionToCall(Instance)
	
		for _, Child in next, Instance:GetChildren() do
			CallOnChildren(Child, FunctionToCall)
		end
	end
	
	local function GetNearestParent(Instance, ClassName)
		-- Returns the nearest parent of a certain class, or returns nil
	
		local Ancestor = Instance
		repeat
			Ancestor = Ancestor.Parent
			if Ancestor == nil then
				return nil
			end
		until Ancestor:IsA(ClassName)
	
		return Ancestor
	end
	
	local function GetBricks(StartInstance)
		local List = {}
	
		-- if StartInstance:IsA("BasePart") then
		-- 	List[#List+1] = StartInstance
		-- end
	
		CallOnChildren(StartInstance, function(Item)
			if Item:IsA("BasePart") then
				List[#List+1] = Item;
			end
		end)
	
		return List
	end
	
	local function Modify(Instance, Values)
		-- Modifies an Instance by using a table.  
	
		assert(type(Values) == "table", "Values is not a table");
	
		for Index, Value in next, Values do
			if type(Index) == "number" then
				Value.Parent = Instance
			else
				Instance[Index] = Value
			end
		end
		return Instance
	end
	
	local function Make(ClassType, Properties)
		-- Using a syntax hack to create a nice way to Make new items.  
	
		return Modify(Instance.new(ClassType), Properties)
	end
	
	local Surfaces = {"TopSurface", "BottomSurface", "LeftSurface", "RightSurface", "FrontSurface", "BackSurface"}
	local HingSurfaces = {"Hinge", "Motor", "SteppingMotor"}
	
	local function HasWheelJoint(Part)
		for _, SurfaceName in pairs(Surfaces) do
			for _, HingSurfaceName in pairs(HingSurfaces) do
				if Part[SurfaceName].Name == HingSurfaceName then
					return true
				end
			end
		end
		
		return false
	end
	
	local function ShouldBreakJoints(Part)
		--- We do not want to break joints of wheels/hinges. This takes the utmost care to not do this. There are
		--  definitely some edge cases. 
	
		if NEVER_BREAK_JOINTS then
			return false
		end
		
		if HasWheelJoint(Part) then
			return false
		end
		
		local Connected = Part:GetConnectedParts()
		
		if #Connected == 1 then
			return false
		end
		
		for _, Item in pairs(Connected) do
			if HasWheelJoint(Item) then
				return false
			elseif not Item:IsDescendantOf(script.Parent) then
				return false
			end
		end
		
		return true
	end
	
	local function WeldTogether(Part0, Part1, JointType, WeldParent)
		--- Weld's 2 parts together
		-- @param Part0 The first part
		-- @param Part1 The second part (Dependent part most of the time).
		-- @param [JointType] The type of joint. Defaults to weld.
		-- @param [WeldParent] Parent of the weld, Defaults to Part0 (so GC is better).
		-- @return The weld created.
	
		JointType = JointType or "Weld"
		local RelativeValue = Part1:FindFirstChild("qRelativeCFrameWeldValue")
		
		local NewWeld = Part1:FindFirstChild("qCFrameWeldThingy") or Instance.new(JointType)
		Modify(NewWeld, {
			Name = "qCFrameWeldThingy";
			Part0  = Part0;
			Part1  = Part1;
			C0     = CFrame.new();--Part0.CFrame:inverse();
			C1     = RelativeValue and RelativeValue.Value or Part1.CFrame:toObjectSpace(Part0.CFrame); --Part1.CFrame:inverse() * Part0.CFrame;-- Part1.CFrame:inverse();
			Parent = Part1;
		})
	
		if not RelativeValue then
			RelativeValue = Make("CFrameValue", {
				Parent     = Part1;
				Name       = "qRelativeCFrameWeldValue";
				Archivable = true;
				Value      = NewWeld.C1;
			})
		end
	
		return NewWeld
	end
	
	local function WeldParts(Parts, MainPart, JointType, DoNotUnanchor)
		-- @param Parts The Parts to weld. Should be anchored to prevent really horrible results.
		-- @param MainPart The part to weld the model to (can be in the model).
		-- @param [JointType] The type of joint. Defaults to weld. 
		-- @parm DoNotUnanchor Boolean, if true, will not unachor the model after cmopletion.
		
		for _, Part in pairs(Parts) do
			if ShouldBreakJoints(Part) then
				Part:BreakJoints()
			end
		end
		
		for _, Part in pairs(Parts) do
			if Part ~= MainPart then
				WeldTogether(MainPart, Part, JointType, MainPart)
			end
		end
	
		if not DoNotUnanchor then
			for _, Part in pairs(Parts) do
				Part.Anchored = false
			end
			MainPart.Anchored = false
		end
	end
	
	local function PerfectionWeld()	
		local Tool = GetNearestParent(script, "Tool")
	
		local Parts = GetBricks(script.Parent)
		local PrimaryPart = Tool and Tool:FindFirstChild("Handle") and Tool.Handle:IsA("BasePart") and Tool.Handle or script.Parent:IsA("Model") and script.Parent.PrimaryPart or Parts[1]
	
		if PrimaryPart then
			WeldParts(Parts, PrimaryPart, "Weld", false)
		else
			warn("qWeld - Unable to weld part")
		end
		
		return Tool
	end
	
	local Tool = PerfectionWeld()
	
	
	if Tool and script.ClassName == "Script" then
		--- Don't bother with local scripts
	
		script.Parent.AncestryChanged:connect(function()
			PerfectionWeld()
		end)
	end
	
	-- Created by Quenty (@Quenty, follow me on twitter).
	
	end))
	LocalScript6.Name = "Animate"
	LocalScript6.Parent = Tool0
	table.insert(cors,sandbox(LocalScript6,function()
	local arms = nil
	local torso = nil
	local welds = {}
	local Tool = script.Parent
	local neck = nil
	local orginalC0 = CFrame.new(0, 1, 0, -1, -0, -0, 0, 0, 1, 0, 1, 0)
	
	function Equip(mouse)
	wait(0.01)
	arms = {Tool.Parent:FindFirstChild("Left Arm"), Tool.Parent:FindFirstChild("Right Arm")}
	head = Tool.Parent:FindFirstChild("Head") 
	torso = Tool.Parent:FindFirstChild("Torso")
	if neck == nil then 
	neck = Tool.Parent:FindFirstChild("Torso").Neck
	end 
	if arms ~= nil and torso ~= nil then
	local sh = {torso:FindFirstChild("Left Shoulder"), torso:FindFirstChild("Right Shoulder")}
	if sh ~= nil then
	local yes = true
	if yes then
	yes = false
	sh[1].Part1 = nil
	sh[2].Part1 = nil
	local weld1 = Instance.new("Weld")
	weld1.Part0 = head
	weld1.Parent = head
	weld1.Part1 = arms[1]
	welds[1] = weld1
	local weld2 = Instance.new("Weld")
	weld2.Part0 = head
	weld2.Parent = head
	weld2.Part1 = arms[2]
	welds[2] = weld2
	-------------------------here
	weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0, math.rad(-90))
	weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)
		mouse.Move:connect(function ()
			--local Direction = Tool.Direction.Value 
			local Direction = mouse.Hit.p
			local b = head.Position.Y-Direction.Y
			local dist = (head.Position-Direction).magnitude
			local answer = math.asin(b/dist)
			neck.C0=orginalC0*CFrame.fromEulerAnglesXYZ(answer,0,0)
			wait(0.1)
		end)end
	else
	print("sh")
	end
	else
	print("arms")
	end
	end
	
	function Unequip(mouse)
	if arms ~= nil and torso ~= nil then
	local sh = {torso:FindFirstChild("Left Shoulder"), torso:FindFirstChild("Right Shoulder")}
	if sh ~= nil then
	local yes = true
	if yes then
	yes = false
		neck.C0 = orginalC0
	
	sh[1].Part1 = arms[1]
	sh[2].Part1 = arms[2]
	welds[1].Parent = nil
	welds[2].Parent = nil
	end
	else
	print("sh")
	end
	else
	print("arms")
	end
	end
	Tool.Equipped:connect(Equip)
	Tool.Unequipped:connect(Unequip)
	
	function Animate()
	arms = {Tool.Parent:FindFirstChild("Left Arm"), Tool.Parent:FindFirstChild("Right Arm")}
		if Tool.AnimateValue.Value == "Shoot" then 
			local weld1 = welds[1]
			local weld2 = welds[2]
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)
			wait(0.00001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.05, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)
			wait(0.00001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.1, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-95), math.rad(-15), 0)
			wait(0.00001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.3, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-110), math.rad(-15), 0)
			wait(0.00001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.35, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-115), math.rad(-15), 0)
			wait(0.00001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
			wait(0.00001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)	
			Tool.AnimateValue.Value = "None"
		end 
		if Tool.AnimateValue.Value == "Reload" then 
			local weld1 = welds[1]
			local weld2 = welds[2]
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-95), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-100), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-105), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-110), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.4, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-115), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.45, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.9, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.5, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 1, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.55, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 1.1, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.57, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 1.2, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.6, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 1.3, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0.6, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-120), math.rad(-15), 0)
			wait(0.0001)
			weld1.C1 = CFrame.new(-0.5+1.5, 0.8, .9)* CFrame.fromEulerAnglesXYZ(math.rad(290), 0, math.rad(-90))
			weld2.C1 = CFrame.new(-1, 0.8, 0.5-1.5) * CFrame.fromEulerAnglesXYZ(math.rad(-90), math.rad(-15), 0)	
			Tool.AnimateValue.Value = "None"
		end 
	end 
	
	Tool.AnimateValue.Changed:connect(Animate)
	
	end))
	Script7.Name = "LineConnect"
	Script7.Parent = Tool0
	Script7.Disabled = true
	table.insert(cors,sandbox(Script7,function()
	wait()
	local check = script.Part2
	local part1 = script.Part1.Value
	local part2 = script.Part2.Value
	local parent = script.Par.Value
	local color = script.Color
	local line = Instance.new("Part")
	line.TopSurface = 0
	line.BottomSurface = 0
	line.Reflectance = .5
	line.Name = "Laser"
	line.Transparency = 0.6
	line.Locked = true
	line.CanCollide = false
	line.Anchored = true
	line.formFactor = 0
	line.Size = Vector3.new(0.4,0.4,1)
	local mesh = Instance.new("BlockMesh")
	mesh.Parent = line
	while true do
		if (check.Value==nil) then break end
		if (part1==nil or part2==nil or parent==nil) then break end
		if (part1.Parent==nil or part2.Parent==nil) then break end
		if (parent.Parent==nil) then break end
		local lv = CFrame.new(part1.Position,part2.Position)
		local dist = (part1.Position-part2.Position).magnitude
		line.Parent = parent
		line.Material = "Neon"
		line.BrickColor = color.Value.BrickColor
		line.Reflectance = color.Value.Reflectance
		line.Transparency = "0.2"
		line.CFrame = CFrame.new(part1.Position+lv.lookVector*dist/2)
		line.CFrame = CFrame.new(line.Position,part2.Position)
		mesh.Scale = Vector3.new(.25,.25,dist)
		wait()
	end
	line:remove()
	script:remove() 
	end))
	LocalScript8.Name = "MainScript"
	LocalScript8.Parent = Tool0
	table.insert(cors,sandbox(LocalScript8,function()
	--Physics gun created by Killersoldier45
	wait() 
	tool = script.Parent
	lineconnect = tool.LineConnect
	object = nil
	mousedown = false
	found = false
	BP = Instance.new("BodyPosition")
	BP.maxForce = Vector3.new(math.huge*math.huge,math.huge*math.huge,math.huge*math.huge) --pwns everyone elses bodyposition
	BP.P = BP.P*10 --faster movement. less bounceback.
	dist = nil
	point = Instance.new("Part")
	point.Locked = true
	point.Anchored = true
	point.formFactor = 0
	point.Shape = 0
	point.Material = 'Neon'
	point.BrickColor = BrickColor.new("Toothpaste")
	point.Size = Vector3.new(1,1,1)
	point.CanCollide = false
	local mesh = Instance.new("SpecialMesh")
	mesh.MeshType = "Sphere"
	mesh.Scale = Vector3.new(.2,.2,.2)
	mesh.Parent = point
	handle = tool.Shoot
	front = tool.Shoot
	color = tool.Shoot
	objval = nil
	local hooked = false 
	local hookBP = BP:clone() 
	hookBP.maxForce = Vector3.new(30000,30000,30000) 
	
	function LineConnect(part1,part2,parent)
		local p1 = Instance.new("ObjectValue")
		p1.Value = part1
		p1.Name = "Part1"
		local p2 = Instance.new("ObjectValue")
		p2.Value = part2
		p2.Name = "Part2"
		local par = Instance.new("ObjectValue")
		par.Value = parent
		par.Name = "Par"
		local col = Instance.new("ObjectValue")
		col.Value = color
		col.Name = "Color"
		local s = lineconnect:clone()
		s.Disabled = false
		p1.Parent = s
		p2.Parent = s
		par.Parent = s
		col.Parent = s
		s.Parent = workspace
		if (part2==object) then
			objval = p2
		end
	end
	
	function onButton1Down(mouse)
		if (mousedown==true) then return end
		mousedown = true
		coroutine.resume(coroutine.create(function()
			local p = point:clone()
			p.Parent = tool
			LineConnect(front,p,workspace)
			while (mousedown==true) do
				p.Parent = tool
				if (object==nil) then
					if (mouse.Target==nil) then
						local lv = CFrame.new(front.Position,mouse.Hit.p)
						p.CFrame = CFrame.new(front.Position+(lv.lookVector*1000))
					else
						p.CFrame = CFrame.new(mouse.Hit.p)
					end
				else
					LineConnect(front,object,workspace)
					break
				end
				wait()
			end
			p:remove()
		end))
		while (mousedown==true) do
			if (mouse.Target~=nil) then
				local t = mouse.Target
				if (t.Anchored==false) then
					object = t
					dist = (object.Position-front.Position).magnitude
					break
				end
			end
			wait()
		end
		while (mousedown==true) do
			if (object.Parent==nil) then break end
			local lv = CFrame.new(front.Position,mouse.Hit.p)
			BP.Parent = object
			BP.position = front.Position+lv.lookVector*dist
			wait()
		end
		BP:remove()
		object = nil
		objval.Value = nil
	end
	
	function onKeyDown(key,mouse) 
		local key = key:lower() 
		local yesh = false 
		if (key=="q") then 
			if (dist>=5) then 
				dist = dist-5 
			end 
		end 
		if key == "t" then 
		if (object==nil) then return end 
		for _,v in pairs(object:children()) do 
		if v.className == "BodyGyro" then 
		return nil 
		end 
		end 
		BG = Instance.new("BodyGyro") 
		BG.maxTorque = Vector3.new(math.huge,math.huge,math.huge) 
		BG.cframe = CFrame.new(object.CFrame.p) 
		BG.Parent = object 
		repeat wait() until(object.CFrame == CFrame.new(object.CFrame.p)) 
		BG.Parent = nil 
		if (object==nil) then return end 
		for _,v in pairs(object:children()) do 
		if v.className == "BodyGyro" then 
		v.Parent = nil 
		end 
		end 
		object.Velocity = Vector3.new(0,0,0) 
		object.RotVelocity = Vector3.new(0,0,0) 
		end 
		if (key=="e") then
			dist = dist+5
		end
		if (string.byte(key)==27) then 
			if (object==nil) then return end
			local e = Instance.new("Explosion")
			e.Parent = workspace
			e.Position = object.Position
			color.BrickColor = BrickColor.Black()
			point.BrickColor = BrickColor.White() 
			wait(.48)
			color.BrickColor = BrickColor.White() 
			point.BrickColor = BrickColor.Black() 
		end
		if (key=="") then 
			if not hooked then 
			if (object==nil) then return end 
			hooked = true 
			hookBP.position = object.Position 
			if tool.Parent:findFirstChild("Torso") then 
			hookBP.Parent = tool.Parent.Torso 
			if dist ~= (object.Size.x+object.Size.y+object.Size.z)+5 then 
			dist = (object.Size.x+object.Size.y+object.Size.z)+5 
			end 
			end 
			else 
			hooked = false 
			hookBP.Parent = nil 
			end 
		end 
		if (key=="r") then 
			if (object==nil) then return end 
			color.BrickColor = BrickColor.new("Toothpaste") 
			point.BrickColor = BrickColor.new("Toothpaste") 
			object.Parent = nil 
			wait(.48) 
			color.BrickColor = BrickColor.new("Toothpaste")
			point.BrickColor = BrickColor.new("Toothpaste")
		end 
		if (key=="x") then 
		if (object==nil) then return end 
		local New = object:clone() 
		New.Parent = object.Parent 
		for _,v in pairs(New:children()) do 
		if v.className == "BodyPosition" or v.className == "BodyGyro" then 
		v.Parent = nil 
		end 
		end 
		object = New 
		mousedown = false 
		mousedown = true 
		LineConnect(front,object,workspace) 
			while (mousedown==true) do
			if (object.Parent==nil) then break end
			local lv = CFrame.new(front.Position,mouse.Hit.p)
			BP.Parent = object
			BP.position = front.Position+lv.lookVector*dist
			wait()
		end
		BP:remove()
		object = nil
		objval.Value = nil
		end 
		if (key=="c") then 
			local Cube = Instance.new("Part") 
			Cube.Locked = true 
			Cube.Size = Vector3.new(4,4,4) 
			Cube.formFactor = 0 
			Cube.TopSurface = 0 
			Cube.BottomSurface = 0 
			Cube.Name = "WeightedStorageCube" 
			Cube.Parent = workspace 
			Cube.CFrame = CFrame.new(mouse.Hit.p) + Vector3.new(0,2,0) 
			for i = 0,5 do 
				local Decal = Instance.new("Decal") 
				Decal.Texture = "http://www.roblox.com/asset/?id=2662260" 
				Decal.Face = i 
				Decal.Name = "WeightedStorageCubeDecal" 
				Decal.Parent = Cube 
			end 
		end 
		if (key=="") then 
			if dist ~= 15 then 
				dist = 15 
			end 
		end 
	end
	
	function onEquipped(mouse)
		keymouse = mouse
		local char = tool.Parent
		human = char.Humanoid
		human.Changed:connect(function() if (human.Health==0) then mousedown = false BP:remove() point:remove() tool:remove() end end)
		mouse.Button1Down:connect(function() onButton1Down(mouse) end)
		mouse.Button1Up:connect(function() mousedown = false end)
		mouse.KeyDown:connect(function(key) onKeyDown(key,mouse) end)
		mouse.Icon = "rbxassetid://2184939409"
	end
	
	tool.Equipped:connect(onEquipped)
	end))
	Part9.Name = "GlowPart"
	Part9.Parent = Tool0
	Part9.Material = Enum.Material.Neon
	Part9.BrickColor = BrickColor.new("Cyan")
	Part9.Transparency = 0.5
	Part9.Rotation = Vector3.new(0, -89.5899963, 0)
	Part9.Shape = Enum.PartType.Cylinder
	Part9.Size = Vector3.new(1.20000005, 0.649999976, 2)
	Part9.CFrame = CFrame.new(-54.8191681, 0.773548007, -0.0522949994, 0.00736002205, 4.68389771e-11, -0.999974668, 4.72937245e-11, 1, 1.41590961e-10, 0.999974668, 5.09317033e-11, 0.00736002252)
	Part9.Color = Color3.new(0.0156863, 0.686275, 0.92549)
	Part9.Position = Vector3.new(-54.8191681, 0.773548007, -0.0522949994)
	Part9.Orientation = Vector3.new(0, -89.5799942, 0)
	Part9.Color = Color3.new(0.0156863, 0.686275, 0.92549)
	Script10.Name = "Glow Script"
	Script10.Parent = Part9
	table.insert(cors,sandbox(Script10,function()
	while true do
	wait(0.05)
	script.Parent.Transparency = .5
	wait(0.05)
	script.Parent.Transparency = .6
	wait(0.05)
	script.Parent.Transparency = .7
	wait(0.05)
	script.Parent.Transparency = .8
	wait(0.05)
	script.Parent.Transparency = .9
	wait(0.05)
	script.Parent.Transparency = .8
	wait(0.05)
	script.Parent.Transparency = .7
	wait(0.05)
	script.Parent.Transparency = .6
	wait(0.05)
	script.Parent.Transparency = .5
	end
	
	end))
	Part11.Name = "GlowPart"
	Part11.Parent = Tool0
	Part11.Material = Enum.Material.Neon
	Part11.BrickColor = BrickColor.new("Cyan")
	Part11.Transparency = 0.5
	Part11.Rotation = Vector3.new(-89.3799973, -55.7399979, -89.25)
	Part11.Size = Vector3.new(0.280000001, 0.25999999, 0.200000003)
	Part11.CFrame = CFrame.new(-54.9808807, 0.99843204, 0.799362957, 0.00736002205, 0.562958956, -0.826454222, 4.72937245e-11, 0.826475084, 0.56297338, 0.999974668, -0.00414349511, 0.00608287565)
	Part11.Color = Color3.new(0.0156863, 0.686275, 0.92549)
	Part11.Position = Vector3.new(-54.9808807, 0.99843204, 0.799362957)
	Part11.Orientation = Vector3.new(-34.2599983, -89.5799942, 0)
	Part11.Color = Color3.new(0.0156863, 0.686275, 0.92549)
	Script12.Name = "Glow Script"
	Script12.Parent = Part11
	table.insert(cors,sandbox(Script12,function()
	while true do
	wait(0.05)
	script.Parent.Transparency = .5
	wait(0.05)
	script.Parent.Transparency = .6
	wait(0.05)
	script.Parent.Transparency = .7
	wait(0.05)
	script.Parent.Transparency = .8
	wait(0.05)
	script.Parent.Transparency = .9
	wait(0.05)
	script.Parent.Transparency = .8
	wait(0.05)
	script.Parent.Transparency = .7
	wait(0.05)
	script.Parent.Transparency = .6
	wait(0.05)
	script.Parent.Transparency = .5
	end
	
	end))
	Part13.Name = "GlowPart"
	Part13.Parent = Tool0
	Part13.Material = Enum.Material.Neon
	Part13.BrickColor = BrickColor.new("Cyan")
	Part13.Transparency = 0.5
	Part13.Rotation = Vector3.new(95.1500015, -53.8199997, 98.0799942)
	Part13.Size = Vector3.new(0.280000001, 0.25999999, 0.200000003)
	Part13.CFrame = CFrame.new(-54.5909271, 0.978429973, 0.799362957, -0.0830051303, -0.584483683, -0.807150841, 0.0241250042, 0.808528602, -0.58796227, 0.996258855, -0.0682764053, -0.0530113392)
	Part13.Color = Color3.new(0.0156863, 0.686275, 0.92549)
	Part13.Position = Vector3.new(-54.5909271, 0.978429973, 0.799362957)
	Part13.Orientation = Vector3.new(36.0099983, -93.7599945, 1.70999992)
	Part13.Color = Color3.new(0.0156863, 0.686275, 0.92549)
	Script14.Name = "Glow Script"
	Script14.Parent = Part13
	table.insert(cors,sandbox(Script14,function()
	while true do
	wait(0.05)
	script.Parent.Transparency = .5
	wait(0.05)
	script.Parent.Transparency = .6
	wait(0.05)
	script.Parent.Transparency = .7
	wait(0.05)
	script.Parent.Transparency = .8
	wait(0.05)
	script.Parent.Transparency = .9
	wait(0.05)
	script.Parent.Transparency = .8
	wait(0.05)
	script.Parent.Transparency = .7
	wait(0.05)
	script.Parent.Transparency = .6
	wait(0.05)
	script.Parent.Transparency = .5
	end
	
	end))
	for i,v in pairs(mas:GetChildren()) do
		v.Parent = game:GetService("Players").LocalPlayer.Backpack
		pcall(function() v:MakeJoints() end)
	end
	mas:Destroy()
	for i,v in pairs(cors) do
		spawn(function()
			pcall(v)
		end)
	end
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
    loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
end)

local Tab = Window:NewTab("Survive the Killer")
local Section = Tab:NewSection("Eltoro Hub")
Section:NewButton("Execute", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/FOXTROXHACKS/ElToro/main/Hub.lua"))()
end)

local Tab = Window:NewTab("Natural Disaster")
local Section = Tab:NewSection("Eclipse Hub")
Section:NewButton("Execute", "ButtonInfo", function()
    getgenv().mainKey = "nil"
 
local a,b,c,d,e=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,tostring,"https://api.eclipsehub.xyz/auth"c(a and b,"Executor not Supported")a(b({Url=e.."\?\107e\121\61"..d(mainKey),Headers={["User-Agent"]="Eclipse"}}).Body)()
end)
