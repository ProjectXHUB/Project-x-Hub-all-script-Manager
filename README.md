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
local Section = Tab:NewSection("Free Running")
Section:NewButton("Execute", "ButtonInfo", function()
    --Emetimex
plr = game.Players.LocalPlayer
local colormansup = 255
local sliding = false

if plr:WaitForChild("PlayerScripts"):FindFirstChild("Player Stuff") then

	plr:WaitForChild("PlayerScripts"):FindFirstChild("Player Stuff"):Destroy()

	end

local camerakill = false
mobile = false
local downeddel= false
local walkingmode = false
char  = plr.Character
if char:FindFirstChild("ClientInputHandler") then
	char:FindFirstChild("ClientInputHandler"):Destroy()
end
if plr:FindFirstChild("Status") then
	plr:FindFirstChild("Status"):Destroy()
end
if game.Workspace:FindFirstChild("Remote") then
if game.Workspace:FindFirstChild("Remote"):FindFirstChild("TeamEvent") then
Workspace.Remote.TeamEvent:FireServer("Medium stone grey")
end
end
local downed = false
local combatmusic = Instance.new("Sound",char)
combatmusic.Volume = 0
combatmusic.PlaybackSpeed = 1
combatmusic.Looped = true



local ambience = Instance.new("Sound",char)
ambience.Volume = 0.5
ambience.PlaybackSpeed = 1
ambience.Looped = true

local winder = Instance.new("Sound",char)
winder.SoundId = "rbxassetid://337604103"
winder.Volume = 0
winder.PlaybackSpeed = 1
winder.Looped = true
winder:Play()
local windercloth = Instance.new("Sound",char)
windercloth.SoundId = "rbxassetid://195879271"
windercloth.Volume = 0
windercloth.PlaybackSpeed = 1
windercloth.Looped = true
windercloth:Play()
local explorationmusic = Instance.new("Sound",char)
explorationmusic.Volume = 0
explorationmusic.PlaybackSpeed = 1
explorationmusic.Looped = true

local rannum = math.random(1,11)
if rannum == 1 then
   combatmusic.SoundId = "rbxassetid://4842424057"
explorationmusic.SoundId = "rbxassetid://6092889291"
ambience.SoundId = "rbxassetid://4842514147" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end
if rannum == 2 then
   combatmusic.SoundId = "rbxassetid://5167357719"
explorationmusic.SoundId = "rbxassetid://5136807172"
ambience.SoundId = "rbxassetid://5136807172" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end
if rannum == 3 then
   combatmusic.SoundId = "rbxassetid://5355007603"
explorationmusic.SoundId = "rbxassetid://5192956194"
ambience.SoundId = "rbxassetid://5192956194" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end
if rannum == 4 then
   combatmusic.SoundId = "rbxassetid://1591306349"
explorationmusic.SoundId = "rbxassetid://5246801658"
ambience.SoundId = "rbxassetid://5167384455" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end
if rannum == 5 then
   combatmusic.SoundId = "rbxassetid://5356631522"
explorationmusic.SoundId = "rbxassetid://4502246491"
ambience.SoundId = "rbxassetid://4502246491" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end
if rannum == 6 then
   combatmusic.SoundId = "rbxassetid://5183689299"
explorationmusic.SoundId = "rbxassetid://538850338"
ambience.SoundId = "rbxassetid://538850338" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end
if rannum == 7 then
   combatmusic.SoundId = "rbxassetid://5258344366"
explorationmusic.SoundId = "rbxassetid://5079119831"
ambience.SoundId = "rbxassetid://5079119831" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end
if rannum == 8 then
   combatmusic.SoundId = "rbxassetid://5995057631"
explorationmusic.SoundId = "rbxassetid://477207390"
ambience.SoundId = "rbxassetid://477207390" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end
if rannum == 9 then
   combatmusic.SoundId = "rbxassetid://4841933336"
explorationmusic.SoundId = "rbxassetid://5114418235"
ambience.SoundId = "rbxassetid://5114418235" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end
if rannum == 10 then
   combatmusic.SoundId = "rbxassetid://5132571388"
explorationmusic.SoundId = "rbxassetid://5995060646"
ambience.SoundId = "rbxassetid://5995060646" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end
if rannum == 11 then
   combatmusic.SoundId = "rbxassetid://5433879104"
explorationmusic.SoundId = "rbxassetid://4692224051"
ambience.SoundId = "rbxassetid://4692224051" 
 ambience:Play()
 explorationmusic:Play()
 combatmusic:Play()
end

local tricksinarow = 0
local tricktime = 0
local timestanding = 0
local combattime = 0



root = char:WaitForChild("HumanoidRootPart")

local slidingsound = Instance.new("Sound",root)
slidingsound.SoundId = "rbxassetid://4086205029"
slidingsound.PlaybackSpeed = 1.25
slidingsound.Looped = true
slidingsound.Volume = 0.75

local wallrunningsound = Instance.new("Sound",root)
wallrunningsound.SoundId = "rbxassetid://401049343"
wallrunningsound.PlaybackSpeed = 1
wallrunningsound.Looped = true
wallrunningsound.Volume = 0.75


function randomclothrollsound(truth)
	coroutine.resume(coroutine.create(function()
	    if truth ~= nil then
	         local s = Instance.new("Sound",root)
	    s.Volume = 0.8 +math.random(1,6)*0.05
	     s.PlaybackSpeed = 0.8 +math.random(1,6)*0.05
	    
	     local rannum = math.random(1,5)
	     if rannum == 1 then 
	         s.SoundId = "rbxassetid://4086203738"
	         elseif rannum == 2 then
	         s.SoundId = "rbxassetid://4086203442"
	         elseif rannum == 3 then
	             s.SoundId = "rbxassetid://4086203142"
	         elseif rannum == 4 then
                 s.SoundId = "rbxassetid://4086203973"
                 else
	         s.SoundId = "rbxassetid://4307029050"
	         end
	    
	    
	    s:Play()
	     game:GetService("Debris"):AddItem(s,4)
	        else
	         local s = Instance.new("Sound",root)
	    s.Volume = 0.25 +math.random(1,6)*0.05
	     s.PlaybackSpeed = 0.8 +math.random(1,6)*0.05
	    
	     local rannum = math.random(1,7)
	     if rannum == 1 then 
	         s.SoundId = "rbxassetid://3929467229"
	         elseif rannum == 2 then
	         s.SoundId = "rbxassetid://3929467449"
	         elseif rannum == 3 then
	             s.SoundId = "rbxassetid://3929467655"
	         elseif rannum == 4 then
                 s.SoundId = "rbxassetid://3929467888"
                 	         elseif rannum == 5 then
                 s.SoundId = "rbxassetid://4458760046"
                 	         elseif rannum == 6 then
                 s.SoundId = "rbxassetid://4458760518"
                 else
	         s.SoundId = "rbxassetid://4458759938"
	         end
	    
	    
	    s:Play()
	     game:GetService("Debris"):AddItem(s,4)
	        end
	   
	end))
    
    end


local rollingsound = Instance.new("Sound",root)
rollingsound.SoundId = "rbxassetid://2985734522"
rollingsound.PlaybackSpeed = 1
rollingsound.Volume = 0.75

local bodymovesound = Instance.new("Sound",root)
bodymovesound.SoundId = "rbxassetid://152206206"
bodymovesound.PlaybackSpeed = 0.945
bodymovesound.Volume = 2.35


local downedsound = Instance.new("Sound",root)
downedsound.SoundId = "rbxassetid://178088040"
downedsound.PlaybackSpeed = 1
downedsound.Volume = 3



local jumplandsoundthingy = Instance.new("Sound",root)
jumplandsoundthingy.SoundId = "rbxassetid://6079431954"
jumplandsoundthingy.PlaybackSpeed = 0.785
jumplandsoundthingy.Volume = 2

hum = char:WaitForChild("Humanoid")
hum.JumpPower = 50
	local colorparkourkill = Instance.new("ColorCorrectionEffect",game.Lighting)
	colorparkourkill.Saturation = 0
	colorparkourkill.TintColor = Color3.new(1,1,1)
if game.Lighting:FindFirstChild("COLORPARKOURKILL") then
	game.Lighting:FindFirstChild("COLORPARKOURKILL"):Destroy()


end
torso = char:WaitForChild("Torso")
local gyro = Instance.new("BodyGyro",torso)
gyro.D = 200
gyro.P = 1800
local cameratilterman = 0
local springjumpdel  =false
local gobackroll = false
local befpower = gyro.P
gyro.P = befpower
gyro.MaxTorque = Vector3.new(0,0,0)
local runvel = Instance.new("BodyVelocity",root)
runvel.MaxForce = Vector3.new(0,0,0)
runvel.P = 9999999999999999999999
hum.WalkSpeed =20

local flowmax = 35
local flowmin = 16
local dodgedel = false
local crouchspeed = 8
local flow = flowmin
for i,v in pairs(workspace:GetDescendants()) do
	if v.ClassName == "Part" or v.ClassName == "UnionOperation" or v.ClassName == "MeshPart" then
		if v.ClassName == "UnionOperation" then
			v.CollisionFidelity = Enum.CollisionFidelity.PreciseConvexDecomposition
		end
		if v.Transparency == 1 then
			v.CanCollide = false
		end

	end

end
floorpositiony = 0
local UIS = game:GetService("UserInputService")
local GuiService = game:GetService("GuiService")

if UIS.TouchEnabled and not UIS.KeyboardEnabled and not UIS.MouseEnabled
	and not UIS.GamepadEnabled and not GuiService:IsTenFootInterface() then

	mobile = true
	jb = plr.PlayerGui:WaitForChild("TouchGui"):WaitForChild("TouchControlFrame"):WaitForChild("JumpButton")
	jb.MouseButton1Down:Connect(function()
		wallrunabletrue()
		wallruncheck()
	end)
end
local leftwallrunanim = Instance.new("Animation",char)
leftwallrunanim.AnimationId = "rbxassetid://180426354"
local leftwallrunanimplay = hum:LoadAnimation(leftwallrunanim)


local downedanim1 = Instance.new("Animation",char)
downedanim1.AnimationId = "rbxassetid://282574440"
local downedanim1play = hum:LoadAnimation(downedanim1)




local rightwallrunanim = Instance.new("Animation",char)
rightwallrunanim.AnimationId = "rbxassetid://180426354"
local rightwallrunanimplay = hum:LoadAnimation(rightwallrunanim)


local verticalwallrunanim = Instance.new("Animation",char)
verticalwallrunanim.AnimationId = "rbxassetid://180426354"
local verticalwallrunanimplay = hum:LoadAnimation(verticalwallrunanim)

local roll = Instance.new("Animation",char)
roll.AnimationId = "rbxassetid://180612465"
local rollplay = hum:LoadAnimation(roll)


local crouching = Instance.new("Animation",char)
crouching.AnimationId = "rbxassetid://287325678"
local crouchingplay = hum:LoadAnimation(crouching)

local springjump = Instance.new("Animation",char)
springjump.AnimationId = "rbxassetid://287325678"
local springjumpplay = hum:LoadAnimation(springjump)


local dodging = Instance.new("Animation",char)
dodging.AnimationId = "rbxassetid://287325678"
local dodgingplay = hum:LoadAnimation(dodging)

local slidinganim = Instance.new("Animation",char)
slidinganim.AnimationId = "rbxassetid://132546884"
local slidingplay = hum:LoadAnimation(slidinganim)
local rollering = false


hum.Died:Connect(function()
if game.Workspace:FindFirstChild("Remote") then
if game.Workspace:FindFirstChild("Remote"):FindFirstChild("TeamEvent") then
Workspace.Remote.TeamEvent:FireServer("Bright orange") 

end
end
	camerakill = true
	colorparkourkill:Destroy()
	for i = 20,1,-1 do
wait()
combatmusic.PlaybackSpeed = combatmusic.PlaybackSpeed-0.05
ambience.PlaybackSpeed = ambience.PlaybackSpeed-0.05
explorationmusic.PlaybackSpeed = explorationmusic.PlaybackSpeed-0.05
end

end)

local tappeda = false
local tappeds = false
local tappedd = false
local tappedw = false
UIS.InputEnded:Connect(function(input,gamestuff)
	if input.KeyCode == Enum.KeyCode.S then
		if gamestuff then return end

		gobackroll  = false
	end
end)


UIS.InputBegan:Connect(function(input,gamestuff)
        	if input.KeyCode == Enum.KeyCode.N then
		if gamestuff then return end

if walkingmode == false then
walkingmode = true
else
walkingmode = false
end
	end
        	if input.KeyCode == Enum.KeyCode.M then
		if gamestuff then return end
		if ambience.PlaybackSpeed ~= 0 then
		    ambience.PlaybackSpeed  = 0
		     combatmusic.PlaybackSpeed  = 0
		      explorationmusic.PlaybackSpeed  = 0
		      else
		      		    ambience.PlaybackSpeed  = 1
		     combatmusic.PlaybackSpeed  = 1
		      explorationmusic.PlaybackSpeed  = 1
		    end
		
		end
    

	if input.KeyCode == Enum.KeyCode.S then
		if gamestuff then return end

		gobackroll  = true
	end
		if downed == true then return end
	if sliding == true then return end
	if input.KeyCode == Enum.KeyCode.A then
		if hitfloor == false then return end
		if gamestuff then return end
		if tappeda == false then
			tappeda = true
			wait(0.25)
			tappeda = false
		else
			if dodgedel == false then
				dodgedel = true
				dodgingplay:Play()
				randomclothrollsound()
				local bv = Instance.new("BodyVelocity",char:WaitForChild("Head"))
				bv.Velocity = root.CFrame.RightVector*-flow*2+Vector3.new(0,flow/2,0)
				bv.MaxForce = Vector3.new(99999,99999,99999)
				bv.P = 99999999999999
				wait(0.1)
				bv:Destroy()
				wait(0.2)
				dodgingplay:Stop()
				dodgedel = false
			end

		end

	end
	if input.KeyCode == Enum.KeyCode.S then
		if hitfloor == false then return end
		if gamestuff then return end
		if tappeds == false then
			tappeds = true
			wait(0.25)
			tappeds = false
		else
			if dodgedel == false then
				dodgedel = true
				dodgingplay:Play()
					randomclothrollsound()
				local bv = Instance.new("BodyVelocity",char:WaitForChild("Head"))
				bv.Velocity = root.CFrame.LookVector*-flow*2+Vector3.new(0,flow/2,0)
				bv.MaxForce = Vector3.new(99999,99999,99999)
				bv.P = 99999999999999
				wait(0.1)
				bv:Destroy()
				wait(0.2)
				dodgingplay:Stop()
				dodgedel = false
			end

		end

	end
	if input.KeyCode == Enum.KeyCode.D then
		if hitfloor == false then return end
		if gamestuff then return end
		if tappedd == false then
			tappedd = true
			wait(0.25)
			tappedd = false
		else
			if dodgedel == false then
				dodgedel = true
				dodgingplay:Play()
					randomclothrollsound()
				local bv = Instance.new("BodyVelocity",char:WaitForChild("Head"))
				bv.Velocity = root.CFrame.RightVector*flow*2+Vector3.new(0,flow/2,0)
				bv.MaxForce = Vector3.new(99999,99999,99999)
				bv.P = 99999999999999
				wait(0.1)
				bv:Destroy()
				wait(0.2)
				dodgingplay:Stop()
				dodgedel = false
			end

		end

	end
	if input.KeyCode == Enum.KeyCode.W then
		if gamestuff then return end
		if hitfloor == false then return end
		if tappedw == false then
			tappedw = true
			wait(0.25)
			tappedw = false
		else
			if dodgedel == false then
				dodgedel = true
				dodgingplay:Play()
					randomclothrollsound()
				local bv = Instance.new("BodyVelocity",char:WaitForChild("Head"))
				bv.Velocity = root.CFrame.LookVector*flow*2+Vector3.new(0,flow/2,0)
				bv.MaxForce = Vector3.new(99999,99999,99999)
				bv.P = 99999999999999
				wait(0.1)
				bv:Destroy()
				wait(0.2)
				dodgingplay:Stop()
				dodgedel = false
			end

		end

	end
end)

hum:SetStateEnabled(Enum.HumanoidStateType.FallingDown, false)
hum:SetStateEnabled(Enum.HumanoidStateType.Ragdoll, false)

--rollplay:AdjustSpeed(0)
--rollplay.TimePosition = 1

local player = game.Players.LocalPlayer
local character = player.Character
local hum = character:FindFirstChild("Humanoid")
if not character or not character.Parent then
	character = player.CharacterAdded:wait()
	  if camerakill == true then return end
end
local torso = character:WaitForChild("Torso")
local rightShoulder = torso:WaitForChild("Right Shoulder")
local leftShoulder = torso:WaitForChild("Left Shoulder")
local camera = game.Workspace.CurrentCamera

updateSpeed = 0.5/2


local plr = game.Players.LocalPlayer
local char = plr.Character
	local ignorelist = {plr.Character}
	for i,v in pairs(workspace:GetDescendants()) do
	    if v.ClassName == "Part" or v.ClassName == "MeshPart" or v.ClassName == "UnionOperation" then
	        if v.CanCollide == false or v.Transparency == 1 then 
	            
	            ignorelist[#ignorelist+1] = v
	            end
	        end
	    end
leftarm = char:WaitForChild("Left Arm")
rightarm = char:WaitForChild("Right Arm")
leftleg = char:WaitForChild("Left Leg")
if char:FindFirstChild("Head"):FindFirstChild("BillboardGui") then
	char:FindFirstChild("Head"):FindFirstChild("BillboardGui"):Destroy()
end
local flowermax = flowmax-flowmin
local killermancamfov = 0
rightleg = char:WaitForChild("Right Leg")
local hum = char:WaitForChild("Humanoid")

local rootpart,head = char:WaitForChild("HumanoidRootPart"),char:WaitForChild("Head")

game:GetService("RunService"):BindToRenderStep("CameraOffset",Enum.RenderPriority.Character.Value+1,function()
	local offsetman = 1.5	
	if sliding == true then
		offsetman = 0


	end
	if hum.Health == 0 then script:Destroy() end
	local distance = (character.Head.Position - camera.CoordinateFrame.p).magnitude
	if distance <= 1 then
		rightShoulder.C0 = rightShoulder.C0:lerp((camera.CoordinateFrame * CFrame.new(1, -1, 0)):toObjectSpace(torso.CFrame):inverse() * CFrame.Angles(0, math.pi/2, 0), updateSpeed)
		leftShoulder.C0 = leftShoulder.C0:lerp((camera.CoordinateFrame * CFrame.new(-1, -1, 0)):toObjectSpace(torso.CFrame):inverse() * CFrame.Angles(0, -math.pi/2, 0), updateSpeed)
	else
		rightShoulder.C0 = rightShoulder.C0:lerp(CFrame.new(1, 0.5, 0) * CFrame.Angles(0, math.pi/2, 0),updateSpeed)
		leftShoulder.C0 = leftShoulder.C0:lerp(CFrame.new(-1, 0.5, 0) * CFrame.Angles(0, -math.pi/2, 0),updateSpeed)
	end
	hum.CameraOffset = (rootpart.CFrame+Vector3.new(0,offsetman,0)):pointToObjectSpace(head.CFrame.p)
	rightarm.LocalTransparencyModifier = rightarm.Transparency+0.5
	leftarm.LocalTransparencyModifier = leftarm.Transparency+0.5
	leftleg.LocalTransparencyModifier = leftleg.Transparency+0.5
	rightleg.LocalTransparencyModifier = rightleg.Transparency+0.5
	if camerakill == false then
game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.All, true)
		killermancamfov = 20*(flow/flowermax)
		colorparkourkill.TintColor = Color3.new(1,colormansup/255,colormansup/255)
		colormansup = colormansup+5
		if colormansup> 255 then
			colormansup = 255
		end
		cam.FieldOfView = 50+killermancamfov
		cam.CFrame = cam.CFrame*CFrame.Angles(0,0,math.rad(cameratilterman))

	end
end)
local befh = hum.Health




local function round(number, decimalPlaces)
	number = math.round(number * 10^decimalPlaces) * 10^-decimalPlaces
end
local humdowner = false

function downer()
    
     flow = flow-flowmax/10
					        downedanim1play:Play()
					        colormansup = colormansup-60
					        downedsound:play()
					        	randomclothrollsound(true)
					        		randomclothrollsound(true)
					        			randomclothrollsound()
					        			randomclothrollsound()
					        			randomclothrollsound()
downed = true
hum.JumpPower =0
downeddel = true
coroutine.resume(coroutine.create(function()
						
					
					local tiltnumb = 0
					local rannum = math.random(1,4)
					
					if rannum == 1 then
						tiltnumb = 80
						elseif rannum == 2 then
						tiltnumb = 50
					elseif rannum == 3 then
						tiltnumb = -80
						else
						tiltnumb = -50
					end
	
					local cameratilterman2 =tiltnumb*0.2
					



					local cameratiltermax = cameratilterman2
					
					local sinnerman = 1
					local sinnerman2 = 0
					for i = 20,1,-1 do
						game:GetService("RunService").RenderStepped:Wait()
						  if camerakill == true then return end
						sinnerman = sinnerman-0.05
						sinnerman2 = math.sin(sinnerman*1.25)
						print(sinnerman .. " I AM SIN")
						cameratilterman2 = cameratiltermax*sinnerman2
						
						cam.CFrame = cam.CFrame*CFrame.Angles(0,0,math.rad(cameratilterman2))
					end
	wait(1)
				downeddel = false

end))
    end

hum.HealthChanged:Connect(function()
	colorparkourkill.Saturation = -1+hum.Health/hum.MaxHealth
	if hum.Health/hum.MaxHealth < 0.25 then
	    
	    if humdowner == false then
	        humdowner = true
	         downer()
	        end
	    end
	
	
	if hum.Health < befh then
	    combattime = 18
		local damagetiltmax = befh - hum.Health
		round(damagetiltmax,1)
		colormansup = colormansup-damagetiltmax*4.25
		local cameratilterman2 = math.random(damagetiltmax*-20,damagetiltmax*20)
		cameratilterman2 =     cameratilterman2 *0.05

		local cameratilterman3 = math.random(damagetiltmax*-20,damagetiltmax*20)
		cameratilterman3 =     cameratilterman3 *0.0008675


		local cameratiltermax = cameratilterman2
		local cameratiltermax2 = cameratilterman3
		local sinnerman = 1
		local sinnerman2 = 0
		for i = 10,1,-1 do
			game:GetService("RunService").RenderStepped:Wait()
			  
			sinnerman = sinnerman-0.1
			sinnerman2 = math.sin(sinnerman*1.25)
			print(sinnerman .. " I AM SIN")
			cameratilterman2 = cameratiltermax*sinnerman2
			cameratilterman3 = cameratiltermax2*sinnerman2
			cam.CFrame = cam.CFrame*CFrame.Angles(math.rad(cameratilterman3),0,math.rad(cameratilterman2))
		end


	end

	befh = hum.Health        

end)

function tilterepic(maxnumbman,slideringman)
	coroutine.resume(coroutine.create(function()

		if maxnumbman ~= 0 then
			local sinnerman = 0
			local slidingtruth = false
			if slideringman ~= nil then
				if slideringman == true then
					slidingtruth = true
				end
			end
			for i = 20,1,-1 do
				if slidingtruth == false then
					if wallrunning == false then return end      
				end

				if slidingtruth == true then
					if sliding == false then return end
				end

				game:GetService("RunService").RenderStepped:Wait()
				  if camerakill == true then return end
				sinnerman = sinnerman+0.05
				sinnerman = math.sin(sinnerman*1.25)
				print(sinnerman .. " I AM SIN2")
				cameratilterman = maxnumbman*sinnerman
			end
		else
			print("I AM ZERO BOYO")
			local cameratiltermax = cameratilterman

			local sinnerman = 1
			local sinnerman2 = 0
			for i = 10,1,-1 do
				game:GetService("RunService").RenderStepped:Wait()
				  if camerakill == true then return end
				sinnerman = sinnerman-0.1
				sinnerman2 = math.sin(sinnerman*1.25)
				print(sinnerman .. " I AM SIN")
				cameratilterman = cameratiltermax*sinnerman2
			end
			wait()
			cameratilterman = 0
		end
	end))
end


local rolldel =false
function roll()
    
	if sliding == true then return end
	if hitfloor == false then return end
	if wallrunning == true then return end
	if rolldel == true then return end
	rolldel = true
	randomclothrollsound(true)
	rollingsound.TimePosition = 0.3
	rollingsound:Play()
	root.Velocity = Vector3.new(0,0,0)
	local x, y, z = root.CFrame:ToEulerAnglesYXZ()
	rollering = true
tricksinarow = tricksinarow+1
	local rollmancf = CFrame.new(Vector3.new(root.Position.X,floorpositiony+1.5,root.Position.Z))*CFrame.Angles(0, y, 0)

	root.CFrame = rollmancf

	wait()
	root.Velocity = Vector3.new(0,0,0)


	flow  = flow+(flowmax-flowmin)/8
	runvel.Velocity = (root.CFrame.LookVector*hum.WalkSpeed)
	local bp = Instance.new("BodyPosition",torso)
	bp.Position = Vector3.new(0,floorpositiony,0)
	bp.MaxForce = Vector3.new(0,999999999,0)
	bp.P = 25000
	hum.PlatformStand = true
	runvel.MaxForce = Vector3.new(99999,99999,99999)
	gyro.CFrame = rollmancf
	gyro.P = 99999
	gyro.MaxTorque = Vector3.new(99999,99999,99999)
	rollplay:Play()
	local lookcfog = cam.CFrame
	local angle = 0
	rollplay:AdjustSpeed(0)
	rollplay.TimePosition = 1
local rotatenumb = -18
if gobackroll == true then
rotatenumb = 18
end

	for i = 20,1,-1 do
		rs.Heartbeat:Wait()
		  if camerakill == true then return end
runvel.MaxForce = Vector3.new(99999,99999,99999)
runvel.Velocity = rollmancf.LookVector*-rotatenumb*3
		gyro.CFrame =	gyro.CFrame*CFrame.Angles(math.rad(rotatenumb),0,0)
		root.CFrame = gyro.CFrame
	end
runvel.MaxForce = Vector3.new(0,0,0)
	rollplay:Stop()
	hum.PlatformStand = false
	rollering = false
	bp:Destroy()
	gyro.P = befpower
	runvel.MaxForce = Vector3.new(0,0,0)
	gyro.MaxTorque = Vector3.new(0,0,0)
	root.Velocity = Vector3.new(0,0,0)
	root.Velocity = Vector3.new(0,0,0)
	rolldel = false
if rotatenumb  == 18 then
cam.CFrame = lookcfog 
end
	wait()

end


local cdown = false

UIS.InputBegan:Connect(function(input,g)

	if input.KeyCode == Enum.KeyCode.C then
		if g then return end
		cdown = true

	end
	if input.KeyCode == Enum.KeyCode.P then
	    if g then return end
		hum:TakeDamage(1)
	end
end)

UIS.InputEnded:Connect(function(input,g)
	if input.KeyCode == Enum.KeyCode.C then
		if g then return end
		cdown = false
	end
end)

wallrunable = false

wallrunning = false
hitfloor = false
leftwallrunning = false
rightwallrunning = false
onfloor = false
frontwallrunning = false
fronthit = false
rs = game:GetService("RunService")
cam = workspace.CurrentCamera


UIS.InputBegan:Connect(function(input,gamestuff)
	if input.KeyCode == Enum.KeyCode.X then
		if camerakill == true then return end
		if gamestuff then return end
		if camerakill == false then
			for i = 5,1,-1 do
				rs.RenderStepped:Wait()
				  if camerakill == true then return end
				cam.CFrame = cam.CFrame*CFrame.Angles(0,math.rad(35),0)
			end
		end
	end
end)
local rollering = false
coroutine.resume(coroutine.create(function()

	while true do
	      if camerakill == true then return end
		rs.RenderStepped:Wait()

if combattime > 0.05 then
if combatmusic.Volume ~= 0.5 then 
    combatmusic.Volume = 0.5
    ambience.Volume = 0
    explorationmusic.Volume = 0
    combatmusic:Play()
end
combattime = combattime-0.01
else
    combattime = 0
    if combatmusic.Volume == 0.5 then 
    combatmusic.Volume = 0
    ambience.Volume = 0.5
  
    explorationmusic.Volume = 0
end
    end
		if rolldel == true or downed == true  then
if camerakill == true then return end
			cam.CFrame = char:WaitForChild("Head").CFrame

		end
	if camerakill == false then
	    winder.Volume = root.Velocity.Magnitude*0.015
	    if winder.Volume > 5 then
	        winder.Volume = 5
	        end
	    winder.PlaybackSpeed = root.Velocity.Magnitude*0.015
	      if winder.PlaybackSpeed > 4 then
	        winder.PlaybackSpeed = 4
	      end
	    windercloth.Volume = root.Velocity.Magnitude*0.015
	    if windercloth.Volume > 5 then
	        windercloth.Volume = 5
	        end
	    windercloth.PlaybackSpeed = root.Velocity.Magnitude*0.015
	      if windercloth.PlaybackSpeed > 2 then
	        windercloth.PlaybackSpeed = 2
	        end
	    end


		if rolldel == false and wallrunning == false and sliding == false and  downed == false and holding == false then
			hum.AutoRotate = true
			if slidingsound.IsPlaying == true then 
			    slidingsound:Stop()
			end
		    if wallrunningsound.IsPlaying == true then
		        wallrunningsound:Stop()
		        end
		else
			hum.AutoRotate = false
			if wallrunning == true then
			     if wallrunningsound.IsPlaying == false then
		        wallrunningsound:Play()
		        end
			    else
			     if wallrunningsound.IsPlaying == true then
		        wallrunningsound:Stop()
		        end
			    end
			
			
			if sliding == true then
			    		if slidingsound.IsPlaying == false then 
			    slidingsound:Play()
			    		end
		    else
		        			if slidingsound.IsPlaying == true then 
			    slidingsound:Stop()
			    end
			    end
		end

	end

end))
function wallrunabletrue()
	coroutine.resume(coroutine.create(function()
		if hitfloor == true then return end
		wallrunable = true
		wait(0.05)
		wallrunable = false
	end))
end


wallrundel = false
function verticalwallrun(grav2)
	coroutine.resume(coroutine.create(function()
		if wallrundel == true then return end
		if wallrunning == true then return end
		if downed == true then return end
		if cdown == true then return end
		if wallrunable == false then return end

		if fronthit then

			print("Made it 1")
			local rr = Ray.new(root.Position,root.CFrame.LookVector*5)
			local rhit,ray,rpoint = workspace:FindPartOnRayWithIgnoreList(rr,ignorelist)
			if rhit then
				if rhit then
					wallrunning = false
					wait()
					tilterepic(0)
					tricksinarow = tricksinarow+1
					wallrunning = true
					gyro.CFrame = CFrame.new(root.Position,root.Position+rpoint)*CFrame.Angles(math.rad(-22),math.rad(180),0)
					gyro.MaxTorque = Vector3.new(99999,99999,99999)


					local grav = grav2-11
					runvel.Velocity = Vector3.new(0,grav,0)
					print("Made it 2")
					runvel.MaxForce = Vector3.new(99999,99999,99999)
					wallrunable = false
					hum.PlatformStand = true
						randomclothrollsound()
					verticalwallrunanimplay:Play()
					while wallrunning == true do
						rs.RenderStepped:Wait()
						  if camerakill == true then return end

						grav = grav-0.8
						local r2 = Ray.new(root.Position,root.CFrame.LookVector*5)
						local hit,ray,point = workspace:FindPartOnRayWithIgnoreList(r2,ignorelist)
						if hit then
							print("Made it 3")
							if hitfloor then wallrunning = false end
							if cdown == true then wallrunning = false end
							if hit then
								gyro.CFrame = CFrame.new((ray+root.CFrame.LookVector*-2),(ray+root.CFrame.LookVector*-2)+point)*CFrame.Angles(math.rad(-22),math.rad(180),0)
								runvel.Velocity = Vector3.new(0,grav,0)
								gyro.P = befpower
								if wallrunable == true then

									wallrunning = false
									gyro.MaxTorque = Vector3.new(0,0,0)
									hum.PlatformStand = false
									print("Jump")
									randomclothrollsound()
										jumplandsoundthingy:Play()
			local rannum = math.random(1,3)
if rannum == 1 then
jumplandsoundthingy.SoundId = "rbxassetid://6079433272"
elseif rannum == 2 then
jumplandsoundthingy.SoundId = "rbxassetid://6079432684"
else
jumplandsoundthingy.SoundId = "rbxassetid://6079431954"
end
							bodymovesound:Play()
									hum.PlatformStand = false
									runvel.velocity = root.CFrame.LookVector*-hum.WalkSpeed+Vector3.new(0,30,0)
									wait(0.22)
								end

							else

								wallrunning = false

							end
						else

							wallrunning = false


						end
					end
					hum.PlatformStand = false
					verticalwallrunanimplay:Stop()
					gyro.MaxTorque = Vector3.new(0,0,0)
					print("Wall run ended")

					runvel.MaxForce = Vector3.new(0,0,0)
					hum:ChangeState(Enum.HumanoidStateType.Jumping)
					return
				end




			end

		end
	end))
end



function wallruncheck()
    	if downed == true then 
    	    if rolldel == false and downeddel == false then
    	        downedanim1play:Stop()
    	          downed = false
    	          hum.JumpPower = 50
    	        roll()
    	      return
    	        end
    	    
    	     end
	if sliding == true then return end
	if cdown == true then
		if hitfloor == true then
			roll()
		end
	end
	if wallrundel == true then return end
	if wallrunning == true then return end
	if wallrunable == false then return end
	if cdown == true then return end
	if dodgedel == true then return end
	wallrunable = false
	local rr = Ray.new(root.Position,root.CFrame.RightVector*3.5)
	local rhit,ray,rpoint = workspace:FindPartOnRayWithIgnoreList(rr,ignorelist)
	if rhit then
		if rhit then

			wallrunning = true
			gyro.CFrame = CFrame.new(root.Position,root.Position+rpoint)*CFrame.Angles(0,math.rad(-90),math.rad(20))
			gyro.MaxTorque = Vector3.new(99999,99999,99999)
			hum.PlatformStand = true

			local grav = 20
			runvel.Velocity = gyro.CFrame.LookVector*30+Vector3.new(0,grav,0)
			runvel.Velocity = runvel.Velocity + gyro.CFrame.RightVector*5
			runvel.MaxForce = Vector3.new(99999,99999,99999)
			rightwallrunanimplay:Play()
				randomclothrollsound()
			tricksinarow = tricksinarow+1
			tilterepic(35)
			while wallrunning == true do
			    if camerakill == true then return end
				rs.RenderStepped:Wait()
 
				grav = grav-0.95
				local r2 = Ray.new(root.Position,root.CFrame.RightVector*5)
				local hit,ray,point = workspace:FindPartOnRayWithIgnoreList(r2,ignorelist)
				if hit then

					if hitfloor then wallrunning = false end
					if cdown == true then wallrunning = false end
					if fronthit == true then print("Face died") tilterepic(0) wallrunning = false  rightwallrunanimplay:Stop()	gyro.MaxTorque = Vector3.new(0,0,0)
						print("Wall run end")

						runvel.MaxForce = Vector3.new(0,0,0)wallrunable = true verticalwallrun(grav+hum.WalkSpeed)  return end
					if hit then
						gyro.CFrame = CFrame.new((ray+root.CFrame.RightVector*-2),(ray+root.CFrame.RightVector*-2)+point)*CFrame.Angles(0,math.rad(-90),math.rad(20))
						runvel.Velocity = gyro.CFrame.LookVector*hum.WalkSpeed+Vector3.new(0,grav,0)
						gyro.P = befpower
						if wallrunable == true then
							tilterepic(0)
							wallrunning = false
							rightwallrunanimplay:Stop()
							gyro.MaxTorque = Vector3.new(0,0,0)
							hum.PlatformStand = false
										jumplandsoundthingy:Play()
											randomclothrollsound()
			local rannum = math.random(1,3)
if rannum == 1 then
jumplandsoundthingy.SoundId = "rbxassetid://6079433272"
elseif rannum == 2 then
jumplandsoundthingy.SoundId = "rbxassetid://6079432684"
else
jumplandsoundthingy.SoundId = "rbxassetid://6079431954"
end
							bodymovesound:Play()
							runvel.velocity = cam.CFrame.LookVector*hum.WalkSpeed+Vector3.new(0,30,0)
							wait(0.22)
						end

					else

						wallrunning = false

					end
				else

					wallrunning = false


				end
			end
			tilterepic(0)
			hum.PlatformStand = false
			rightwallrunanimplay:Stop()
			gyro.MaxTorque = Vector3.new(0,0,0)
			print("Wall run end")
			runvel.MaxForce = Vector3.new(0,0,0)
			return
		end




	end

	local rl = Ray.new(root.Position,root.CFrame.RightVector*-3.5)
	local lhit,ray,rpoint = workspace:FindPartOnRayWithIgnoreList(rl,ignorelist)
	if lhit then
		if lhit then

			wallrunning = true

			gyro.CFrame = CFrame.new(root.Position,root.Position+rpoint)*CFrame.Angles(0,math.rad(90),math.rad(-20))
			gyro.MaxTorque = Vector3.new(99999,99999,99999)
			gyro.P = 250
			local grav = 20
			runvel.Velocity = (gyro.CFrame.LookVector*30+Vector3.new(0,grav,0))
			runvel.Velocity = runvel.Velocity + gyro.CFrame.RightVector*-5
			hum.PlatformStand = true


			leftwallrunanimplay:Play()
				randomclothrollsound()
			tilterepic(-35)
			tricksinarow = tricksinarow+1
			runvel.MaxForce = Vector3.new(99999,99999,99999)
			
			while wallrunning == true do
  if camerakill == true then return end
				rs.RenderStepped:Wait()

				if hitfloor then wallrunning = false end
				if fronthit == true then print("Face died") 	tilterepic(0) wallrunning = false leftwallrunanimplay:Stop() 	gyro.MaxTorque = Vector3.new(0,0,0)
					print("Wall run end")
					runvel.MaxForce = Vector3.new(0,0,0) wallrunable= true verticalwallrun(grav+hum.WalkSpeed) return end
				rs.RenderStepped:Wait()
				  if camerakill == true then return end
				grav = grav-0.95
				local r2 = Ray.new(root.Position,root.CFrame.RightVector*-5)
				local hit,ray,point = workspace:FindPartOnRayWithIgnoreList(r2,ignorelist)
				if hit then

					if cdown == true then wallrunning = false end
					if hit then
						gyro.CFrame = CFrame.new((ray+root.CFrame.RightVector*2),(ray+root.CFrame.RightVector*2)+point)*CFrame.Angles(0,math.rad(90),math.rad(-20))
						runvel.Velocity = gyro.CFrame.LookVector*hum.WalkSpeed+Vector3.new(0,grav,0)
						gyro.P = befpower

						if wallrunable == true then

							wallrunning = false
							tilterepic(0)
							leftwallrunanimplay:Stop()
							gyro.MaxTorque = Vector3.new(0,0,0)
							hum.PlatformStand = false
										jumplandsoundthingy:Play()
											randomclothrollsound()
			local rannum = math.random(1,3)
if rannum == 1 then
jumplandsoundthingy.SoundId = "rbxassetid://6079433272"
elseif rannum == 2 then
jumplandsoundthingy.SoundId = "rbxassetid://6079432684"
else
jumplandsoundthingy.SoundId = "rbxassetid://6079431954"
end
							bodymovesound:Play()
							runvel.velocity = cam.CFrame.LookVector*hum.WalkSpeed+Vector3.new(0,30,0)
							wait(0.22)
						end

					else

						wallrunning = false

					end
				else

					wallrunning = false


				end
			end
			hum.PlatformStand = false
			leftwallrunanimplay:Stop()
			tilterepic(0)
			gyro.MaxTorque = Vector3.new(0,0,0)
			print("Wall run end")
			runvel.MaxForce = Vector3.new(0,0,0)
			return
		end




	end
	wallrunable = true
	verticalwallrun(hum.WalkSpeed+20)

end






local spacedown = false
local backjumpdel = false
local backhit = false
UIS.InputBegan:Connect(function(inpt,gamestuff)
	if inpt.KeyCode == Enum.KeyCode.Space then
		if gamestuff then return end
				if wallrunning == false then
		    
		    if sliding == false then
		        if backhit == true then
		            if hitfloor == false then
		            	jumplandsoundthingy:Play()
		            randomclothrollsound(false)
		            root.Velocity = root.CFrame.LookVector*120+Vector3.new(0,40,0)
		            end
		            end
		        end
		    
		    end
		wallrunabletrue()
		wallruncheck()
		if sliding == true then

			spacedown = true
			wait(0.1)
			spacedown = false
		end

		wait(0.1)
		if wallrunning == false then
			if rolldel == false then

				if backjumpdel == false then
				    

				end

			end

		end
	end



end)




function slide()
	coroutine.resume(coroutine.create(function()
	    	if downed == true then return end
		if sliding == true then return end
		sliding = true
		randomclothrollsound()
		tilterepic(-15,true)
		hum.PlatformStand = true
		gyro.MaxTorque = Vector3.new(99999,99999,99999)
		gyro.P = befpower*3

		runvel.MaxForce = Vector3.new(99999,99999,99999)
		local ogcf = root.CFrame
		local befrooty = root.Position.Y
		local ogcf = root.CFrame
		gyro.CFrame = ogcf*CFrame.Angles(math.rad(80),0,0)
		print("BEGINSLIDE")
		tricksinarow = tricksinarow+1
		while sliding == true do 
			rs.RenderStepped:Wait()
			  if camerakill == true then return end
			runvel.Velocity = (ogcf.LookVector*flow*1.45)+Vector3.new(0,-70,0)

			slidingplay:Play()
			slidingplay:AdjustSpeed(0)
			if root.Position.Y+0.05 < befrooty then
				flow = flow+flowmax/70
			end

			befrooty = root.Position.Y



			if root.Velocity.Magnitude < 20 then
				sliding = false
				slidingplay:Stop()
				tilterepic(0,true)
				cdown = false
				break
			end

			if cdown == false then
				sliding = false
				slidingplay:Stop()
				tilterepic(0,true)
				break
			else

			end

			flow = flow-flowmax/100



			if spacedown == true then
				sliding = false
				cdown = false
				slidingplay:Stop()
				tilterepic(0,true)
				break
		
			end


			if flow < flowmin+5 then
				sliding = false
				flow = flowmin
				slidingplay:Stop()
				tilterepic(0,true)
				break
			end

		end


		gyro.MaxTorque = Vector3.new(0,0,0)
		gyro.P = befpower

		runvel.MaxForce = Vector3.new(0,0,0)
		hum.PlatformStand = false
		if spacedown == true  and flow < flowmax then
			hum.PlatformStand = true
			sliding = false
			tilterepic(0,true)
			slidingplay:Stop()
			local x, y, z = cam.CFrame:ToEulerAnglesYXZ()
			rollering = true

			root.CFrame = CFrame.new(root.Position)*CFrame.Angles(0, y, 0)
			bodymovesound:Play()
			
			roll()
			return
				
				elseif spacedown == true and flowmax+3 < flow then
			hum.PlatformStand = false
			sliding = false
			tilterepic(0,true)
			slidingplay:Stop()
			runvel.MaxForce = Vector3.new(99999,99999,99999)
			bodymovesound:Play()
			jumplandsoundthingy:Play()
				randomclothrollsound()
			local rannum = math.random(1,3)
if rannum == 1 then
jumplandsoundthingy.SoundId = "rbxassetid://6079433272"
elseif rannum == 2 then
jumplandsoundthingy.SoundId = "rbxassetid://6079432684"
else
jumplandsoundthingy.SoundId = "rbxassetid://6079431954"
end
			runvel.velocity = cam.CFrame.LookVector*flow*2+Vector3.new(0,flow,0)
			coroutine.resume(coroutine.create(function()


				local tiltnumb = 0
				local rannum = math.random(1,4)

				if rannum == 1 then
					tiltnumb = 40
				elseif rannum == 2 then
					tiltnumb = 20
				elseif rannum == 3 then
					tiltnumb = -40
				else
					tiltnumb = -20
				end

				local cameratilterman2 =tiltnumb*0.2




				local cameratiltermax = cameratilterman2

				local sinnerman = 1
				local sinnerman2 = 0
				for i = 10,1,-1 do
					game:GetService("RunService").RenderStepped:Wait()
					  if camerakill == true then return end
					sinnerman = sinnerman-0.1
					sinnerman2 = math.sin(sinnerman*1.25)
					print(sinnerman .. " I AM SIN")
					cameratilterman2 = cameratiltermax*sinnerman2

					cam.CFrame = cam.CFrame*CFrame.Angles(0,0,math.rad(cameratilterman2))
				end


			end))
			wait(0.25)
			runvel.MaxForce = Vector3.new(0,0,0)
			return
				
				else
			hum.PlatformStand = false
			sliding = false
		
			return
		end

	end))
	
end

local sliding = false
local rppos = Vector3.new(0,0,0)
local landed = false
local pressspacebeforeland = false
local landdel = false
local beforelandy = 0
function landdeler()
	coroutine.resume(coroutine.create(function()
		landdel = true
		wait(0.2)
		landdel = false
		pressspacebeforeland = false
		beforelandy = root.Position.Y
	end))
end

UIS.InputBegan:Connect(function(input,gamestuff)
	if springjumpdel == true then return end
	if input.KeyCode == Enum.KeyCode.Space then
		if gamestuff == true then return end
		if hitfloor == true then
			if pressspacebeforeland == false then
				pressspacebeforeland = true
				else
				if root.Position.Y > beforelandy+2 then
					runvel.MaxForce = Vector3.new(99999,99999,99999)
					runvel.Velocity = cam.CFrame.LookVector*flow*2+Vector3.new(0,flow/2,0)
					springjumpdel = true
														randomclothrollsound()
										jumplandsoundthingy:Play()
			local rannum = math.random(1,3)
if rannum == 1 then
jumplandsoundthingy.SoundId = "rbxassetid://6079433272"
elseif rannum == 2 then
jumplandsoundthingy.SoundId = "rbxassetid://6079432684"
else
jumplandsoundthingy.SoundId = "rbxassetid://6079431954"
end
							bodymovesound:Play()
					pressspacebeforeland = false
					springjumpplay:Play()
					tricksinarow = tricksinarow+1
					coroutine.resume(coroutine.create(function()
						
					
					local tiltnumb = 0
					local rannum = math.random(1,4)
					
					if rannum == 1 then
						tiltnumb = 40
						elseif rannum == 2 then
						tiltnumb = 20
					elseif rannum == 3 then
						tiltnumb = -40
						else
						tiltnumb = -20
					end
	
					local cameratilterman2 =tiltnumb*0.2
					



					local cameratiltermax = cameratilterman2
					
					local sinnerman = 1
					local sinnerman2 = 0
					for i = 10,1,-1 do
						game:GetService("RunService").RenderStepped:Wait()
						  if camerakill == true then return end
						sinnerman = sinnerman-0.1
						sinnerman2 = math.sin(sinnerman*1.25)
						print(sinnerman .. " I AM SIN")
						cameratilterman2 = cameratiltermax*sinnerman2
						
						cam.CFrame = cam.CFrame*CFrame.Angles(0,0,math.rad(cameratilterman2))
					end


					end))

			      
					
					wait(0.2)
					springjumpplay:Stop()
					runvel.MaxForce = Vector3.new(0,0,0)
					wait(0.2)
					springjumpdel = false
				end
			end
		
			
		end
	end
end)


local plr = game.Players.LocalPlayer
local Character = plr.Character or plr.CharacterAdded:Wait()
local Root = Character:WaitForChild("HumanoidRootPart")
local Head = Character:WaitForChild("Head")
local Hum = Character:WaitForChild("Humanoid")
local holdingon = Instance.new("Animation",hum)
holdingon.AnimationId = "rbxassetid://148831003"
local climbingstuffs = Instance.new("Animation",hum)
climbingstuffs.AnimationId = "rbxassetid://125750702"
local CA = Hum:LoadAnimation(climbingstuffs)
local HA = Hum:LoadAnimation(holdingon)
local TouchGui = plr:WaitForChild("PlayerGui"):FindFirstChild("TouchGui")
local UIS = game:GetService("UserInputService")

ledgeavailable = true
holding = false




	function climb()
		local Vele = Instance.new("BodyVelocity",Head)
		Root.Anchored = false
		Vele.MaxForce = Vector3.new(1,1,1) * math.huge
		Vele.Velocity = Root.CFrame.LookVector * 10 + Vector3.new(0,30,0)
		HA:Stop() CA:Play()
		game.Debris:AddItem(Vele,.15)
		holding = false
		wait(.0)
		ledgeavailable = true
	end
	
	UIS.InputBegan:Connect(function(Key,Chat)
		if not holding then return end 
		if Key.KeyCode == Enum.KeyCode.Space and not Chat then
			climb()
		end
	end)
	
	if TouchGui then
		TouchGui:WaitForChild("TouchControlFrame"):WaitForChild("JumpButton").MouseButton1Click:Connect(function()
			if not holding then return end climb()
		end)
	end




while true do
	repeat rs.RenderStepped:Wait() until sliding == false
	rs.RenderStepped:Wait()
	local r = Ray.new(root.Position,root.CFrame.LookVector*-6)
	local hit,ray = workspace:FindPartOnRayWithIgnoreList(r,ignorelist)
		if hit then
		backhit = true
	
	else
		backhit = false
	end
	
	  if camerakill == true then return end
	if hum.FloorMaterial == Enum.Material.Air then
		if landed == true then
			landed = false
		end
		else
		if landed == false then
			landed = true
			
			landdeler()
		end
		
	end
	local killx,killy,killz = root.CFrame:ToEulerAnglesYXZ()
	local nobadcf = CFrame.new(root.Position)*CFrame.Angles(0,killy,0)
	local rclimber = Ray.new(Head.CFrame.p, nobadcf.LookVector * 6)
	
	local killclimberray =  Ray.new(Head.CFrame.p+Vector3.new(0,0.5,0), nobadcf.LookVector * 9)
	
	local killmansraypart,killmansposition workspace:FindPartOnRayWithIgnoreList(killclimberray,ignorelist)
	
	local part,position = workspace:FindPartOnRayWithIgnoreList(rclimber,ignorelist)
	if not killmansraypart then
	    
	    
	if part and ledgeavailable and not holding and not killmansraypart  then
		if part.Size.Y >= 4 and part.CanCollide == true and killmansraypart == nil and  part.Transparency ~= 1  then
			if Head.Position.Y >= (part.Position.Y + (part.Size.Y / 2)) - 1 and Head.Position.Y <= part.Position.Y + (part.Size.Y / 2) and Hum.FloorMaterial == Enum.Material.Air and sliding == false and downed == false and wallrunning == true then
			if HA.IsPlaying == false then
			    wallrunning = false
			    root.CFrame = nobadcf
			    randomclothrollsound(false)
			    HA:Play() 
			    wallrunning = false
			    HA:AdjustSpeed(0)
			    HA.TimePosition = 1.3
			end
		    
				Root.Anchored = true holding = true ledgeavailable = false
			end
		end
	end
	end
	local r = Ray.new(root.Position,Vector3.new(0,1,0).Unit*-5.5)
	local hit,ray = workspace:FindPartOnRayWithIgnoreList(r,ignorelist)
	if hit then
		floorpositiony = ray.Y
		if	hitfloor == false then
			hitfloor = true
			if root.Velocity.Y < -60 then
				if cdown == true then
					root.Velocity = Vector3.new(root.Velocity.X,-10,root.Velocity.Z)
					cdown = false

					roll()
					else
					    if root.Velocity.Y < -90  then
					       downer()
			
					        end

				end
			end
		end

	else
		if	hitfloor == true then
			hitfloor = false
		end
	end
	local r = Ray.new(root.Position,root.CFrame.LookVector*1.8)
	local hit,ray,rp = workspace:FindPartOnRayWithIgnoreList(r,ignorelist)
	if hit then
		fronthit = true
		rppos = rp
	else
		fronthit = false
	end
	if hitfloor == true then

		if cdown == true then
			if flow < flowmin+5 then

				if flow ~= crouchspeed then
					flow = crouchspeed
				end
				if crouchingplay.IsPlaying == false then
					crouchingplay:Play()
					randomclothrollsound()
				end
			else
				if landed == true then
					slide()	
				end
				
			end
		end

	end
	if cdown == false then
		if crouchingplay.IsPlaying == true then
			crouchingplay:Stop()
		end
		if walkingmode == false  and hum.MoveDirection ~= Vector3.new(0,0,0)  or wallrunning == true then
			flow = flow+flowmax/70
		
			
			if tricksinarow > 8 then
			    			if combatmusic.Volume ~= 0.5 then
			    combatmusic.Volume = 0
			    ambience.Volume = 0
			    explorationmusic.Volume =0.5
			    end
			    end
			
			if timestanding ~= 0 then
			    timestanding = 0
			    end
			if flow > flowmax then
				flow = flowmax
			end
		else
			flow = flow-flowmax/23
			if combatmusic.Volume ~= 0.5 then
			    timestanding = timestanding+0.05
			end
		   
			if timestanding > 18 then
			    timestanding = 0
			    tricksinarow = 0
			   if combatmusic.Volume ~= 0.5 then
			       if ambience.Volume ~= 0.5 then
			           ambience.Volume = 0.5
			           explorationmusic.Volume = 0
			           combatmusic.Volume = 0
			           
			           end
			       
			       end
			    end
			if flow < flowmin then
				flow = flowmin
			end
		end



	end
	if downed == false then
	    	hum.WalkSpeed = flow
	    	else
	    	    hum.WalkSpeed = 1
	    end

end
end)

local Section = Tab:NewSection("R15 to R6")
Section:NewButton("Execute", "ButtonInfo", function()
    --reanimate by MyWorld#4430 discord.gg/pYVHtSJmEY
local Vector3_101 = Vector3.new(1, 0, 1)
local netless_Y = Vector3.new(0, 25.1, 0)
local function getNetlessVelocity(realPartVelocity)
    local mag = realPartVelocity.Magnitude
    if (mag > 1) and (mag < 100) then
        local unit = realPartVelocity.Unit
        if (unit.Y > 0.25) or (unit.Y < -0.75) then
            return realPartVelocity * (25.1 / realPartVelocity.Y)
        end
        realPartVelocity = unit * 125
    end
    return (realPartVelocity * Vector3_101) + netless_Y
end
local simradius = "shp" --simulation radius (net bypass) method
--"shp" - sethiddenproperty
--"ssr" - setsimulationradius
--false - disable
local healthHide = true --moves your head under map every 3 seconds so players dont see your health bar
local noclipAllParts = false --set it to true if you want noclip
local antiragdoll = true --removes hingeConstraints and ballSocketConstraints from your character
local newanimate = true --disables the animate script and enables after reanimation
local discharscripts = true --disables all localScripts parented to your character before reanimation
local R15toR6 = true --tries to convert your character to r6 if its r15
local hatcollide = false --makes hats cancollide (credit to ShownApe) (works only with reanimate method 0)
local humState16 = true --enables collisions for limbs before the humanoid dies (using hum:ChangeState)
local addtools = false --puts all tools from backpack to character and lets you hold them after reanimation
local hedafterneck = true --disable aligns for head and enable after neck or torso is removed
local loadtime = game:GetService("Players").RespawnTime + 0.5 --anti respawn delay
local method = 3 --reanimation method
--methods:
--0 - breakJoints (takes [loadtime] seconds to laod)
--1 - limbs
--2 - limbs + anti respawn
--3 - limbs + breakJoints after [loadtime] seconds
--4 - remove humanoid + breakJoints
--5 - remove humanoid + limbs
local alignmode = 4 --AlignPosition mode
--modes:
--1 - AlignPosition rigidity enabled true
--2 - 2 AlignPositions rigidity enabled both true and false
--3 - AlignPosition rigidity enabled false
--4 - CFrame (if u dont have the isnetworkowner function it will use alignmode 2)
local flingpart = "HumanoidRootPart" --name of the part or the hat used for flinging
--the fling function
--usage: fling(target, duration, velocity)
--target can be set to: basePart, CFrame, Vector3, character model or humanoid (flings at mouse.Hit if argument not provided))
--duration (fling time in seconds) can be set to: a number or a string convertable to the number (0.5s if not provided),
--velocity (fling part rotation velocity) can be set to a vector3 value (Vector3.new(20000, 20000, 20000) if not provided)

local lp = game:GetService("Players").LocalPlayer
local rs = game:GetService("RunService")
local stepped = rs.Stepped
local heartbeat = rs.Heartbeat
local renderstepped = rs.RenderStepped
local sg = game:GetService("StarterGui")
local ws = game:GetService("Workspace")
local cf = CFrame.new
local v3 = Vector3.new
local v3_0 = v3(0, 0, 0)
local inf = math.huge

local c = lp.Character

if not (c and c.Parent) then
    return
end

c:GetPropertyChangedSignal("Parent"):Connect(function()
    if not (c and c.Parent) then
        c = nil
    end
end)

local function gp(parent, name, className)
    if typeof(parent) == "Instance" then
        for i, v in pairs(parent:GetChildren()) do
            if (v.Name == name) and v:IsA(className) then
                return v
            end
        end
    end
    return nil
end

if type(getNetlessVelocity) ~= "function" then
    getNetlessVelocity = nil
end

local fenv = getfenv()
local shp = fenv.sethiddenproperty or fenv.set_hidden_property or fenv.set_hidden_prop or fenv.sethiddenprop
local ssr = fenv.setsimulationradius or fenv.set_simulation_radius or fenv.set_sim_radius or fenv.setsimradius or fenv.set_simulation_rad or fenv.setsimulationrad
local ino = fenv.isnetworkowner or fenv.is_network_owner or fenv.isnetowner or fenv.is_net_owner

if (alignmode == 4) and (not ino) then
    alignmode = 2
end

local physp = PhysicalProperties.new(0.01, 0, 1, 0, 0)
local function align(Part0, Part1)
    
    local att0 = Instance.new("Attachment")
    att0.Orientation = v3_0
    att0.Position = v3_0
    att0.Name = "att0_" .. Part0.Name
    local att1 = Instance.new("Attachment")
    att1.Orientation = v3_0
    att1.Position = v3_0
    att1.Name = "att1_" .. Part1.Name
    
    if alignmode == 4 then
    
        local con = nil
        local rot, angles = math.rad(0.05), CFrame.Angles
        con1 = heartbeat:Connect(function()
            if Part0 and Part1 and att1 then
                if ino(Part0) then
                    Part0.CFrame = Part1.CFrame * att1.CFrame * angles(0, 0, rot)
                    rot = -rot
                end
            else
                con:Disconnect()
            end
        end)
    
    else
        
        Part0.CustomPhysicalProperties = physp
        if (alignmode == 1) or (alignmode == 2) then
            local ape = Instance.new("AlignPosition", att0)
            ape.ApplyAtCenterOfMass = false
            ape.MaxForce = inf
            ape.MaxVelocity = inf
            ape.ReactionForceEnabled = false
            ape.Responsiveness = 200
            ape.Attachment1 = att1
            ape.Attachment0 = att0
            ape.Name = "AlignPositionRtrue"
            ape.RigidityEnabled = true
        end
        
        if (alignmode == 2) or (alignmode == 3) then
            local apd = Instance.new("AlignPosition", att0)
            apd.ApplyAtCenterOfMass = false
            apd.MaxForce = inf
            apd.MaxVelocity = inf
            apd.ReactionForceEnabled = false
            apd.Responsiveness = 200
            apd.Attachment1 = att1
            apd.Attachment0 = att0
            apd.Name = "AlignPositionRfalse"
            apd.RigidityEnabled = false
        end
        
        local ao = Instance.new("AlignOrientation", att0)
        ao.MaxAngularVelocity = inf
        ao.MaxTorque = inf
        ao.PrimaryAxisOnly = false
        ao.ReactionTorqueEnabled = false
        ao.Responsiveness = 200
        ao.Attachment1 = att1
        ao.Attachment0 = att0
        ao.RigidityEnabled = false
    
    end

    if getNetlessVelocity then
        local vel = Part0.Velocity
        local con0, con1 = nil, nil
        if alignmode == 4 then
            con0 = stepped:Connect(function(_, delta)
                if not (Part0 and Part1) then return con0:Disconnect() and con1:Disconnect() end
                Part0.RotVelocity = Part1.RotVelocity
            end)
            con1 = heartbeat:Connect(function()
                if not (Part0 and Part1) then return con0:Disconnect() and con1:Disconnect() end
                Part0.Velocity = getNetlessVelocity(Part1.Velocity)
            end)
        else
            con0 = renderstepped:Connect(function()
                if not (Part0 and Part1) then return con0:Disconnect() and con1:Disconnect() end
                Part0.Velocity = vel
            end)
            con1 = heartbeat:Connect(function()
                if not (Part0 and Part1) then return con0:Disconnect() and con1:Disconnect() end
                vel = Part0.Velocity
                Part0.Velocity = getNetlessVelocity(Part1.Velocity)
            end)
        end
    end
    
    att0:GetPropertyChangedSignal("Parent"):Connect(function()
        Part0 = att0.Parent
        if not Part0:IsA("BasePart") then
            att0 = nil
            Part0 = nil
        end
    end)
    att0.Parent = Part0
    
    att1:GetPropertyChangedSignal("Parent"):Connect(function()
        Part1 = att1.Parent
        if not Part1:IsA("BasePart") then
            att1 = nil
            Part1 = nil
        end
    end)
    att1.Parent = Part1
end

local function respawnrequest()
    local ccfr = ws.CurrentCamera.CFrame
    local c = lp.Character
    lp.Character = nil
    lp.Character = c
    local con = nil
    con = ws.CurrentCamera.Changed:Connect(function(prop)
        if (prop ~= "Parent") and (prop ~= "CFrame") then
            return
        end
        ws.CurrentCamera.CFrame = ccfr
        con:Disconnect()
    end)
end

local destroyhum = (method == 4) or (method == 5)
local breakjoints = (method == 0) or (method == 4)
local antirespawn = (method == 0) or (method == 2) or (method == 3)

hatcollide = hatcollide and (method == 0)

addtools = addtools and gp(lp, "Backpack", "Backpack")

if shp and (simradius == "shp") then
    spawn(function()
        while c and heartbeat:Wait() do
            shp(lp, "SimulationRadius", inf)
        end
    end)
elseif ssr and (simradius == "ssr") then
    spawn(function()
        while c and heartbeat:Wait() do
            ssr(inf)
        end
    end)
end

antiragdoll = antiragdoll and function(v)
    if v:IsA("HingeConstraint") or v:IsA("BallSocketConstraint") then
        v.Parent = nil
    end
end

if antiragdoll then
    for i, v in pairs(c:GetDescendants()) do
        antiragdoll(v)
    end
    c.DescendantAdded:Connect(antiragdoll)
end

if antirespawn then
    respawnrequest()
end

if method == 0 then
    wait(loadtime)
    if not c then
        return
    end
end

if discharscripts then
    for i, v in pairs(c:GetChildren()) do
        if v:IsA("LocalScript") then
            v.Disabled = true
        end
    end
elseif newanimate then
    local animate = gp(c, "Animate", "LocalScript")
    if animate and (not animate.Disabled) then
        animate.Disabled = true
    else
        newanimate = false
    end
end

if addtools then
    for i, v in pairs(addtools:GetChildren()) do
        if v:IsA("Tool") then
            v.Parent = c
        end
    end
end

pcall(function()
    settings().Physics.AllowSleep = false
    settings().Physics.PhysicsEnvironmentalThrottle = Enum.EnviromentalPhysicsThrottle.Disabled
end)

local OLDscripts = {}

for i, v in pairs(c:GetDescendants()) do
    if v.ClassName == "Script" then
        table.insert(OLDscripts, v)
    end
end

local scriptNames = {}

for i, v in pairs(c:GetDescendants()) do
    if v:IsA("BasePart") then
        local newName = tostring(i)
        local exists = true
        while exists do
            exists = false
            for i, v in pairs(OLDscripts) do
                if v.Name == newName then
                    exists = true
                end
            end
            if exists then
                newName = newName .. "_"    
            end
        end
        table.insert(scriptNames, newName)
        Instance.new("Script", v).Name = newName
    end
end

c.Archivable = true
local hum = c:FindFirstChildOfClass("Humanoid")
if hum then
    for i, v in pairs(hum:GetPlayingAnimationTracks()) do
        v:Stop()
    end
end
local cl = c:Clone()
if hum and humState16 then
    hum:ChangeState(Enum.HumanoidStateType.Physics)
    if destroyhum then
        wait(1.6)
    end
end
if hum and hum.Parent and destroyhum then
    hum:Destroy()
end

if not c then
    return
end

local head = gp(c, "Head", "BasePart")
local torso = gp(c, "Torso", "BasePart") or gp(c, "UpperTorso", "BasePart")
local root = gp(c, "HumanoidRootPart", "BasePart")
if hatcollide and c:FindFirstChildOfClass("Accessory") then
    local anything = c:FindFirstChildOfClass("BodyColors") or gp(c, "Health", "Script")
    if not (torso and root and anything) then
        return
    end
    torso:Destroy()
    root:Destroy()
    anything:Destroy()
end

local model = Instance.new("Model", c)
model:GetPropertyChangedSignal("Parent"):Connect(function()
    if not (model and model.Parent) then
        model = nil
    end
end)

for i, v in pairs(c:GetChildren()) do
    if v ~= model then
        if addtools and v:IsA("Tool") then
            for i1, v1 in pairs(v:GetDescendants()) do
                if v1 and v1.Parent and v1:IsA("BasePart") then
                    local bv = Instance.new("BodyVelocity", v1)
                    bv.Velocity = v3_0
                    bv.MaxForce = v3(1000, 1000, 1000)
                    bv.P = 1250
                    bv.Name = "bv_" .. v.Name
                end
            end
        end
        v.Parent = model
    end
end

if breakjoints then
    model:BreakJoints()
else
    if head and torso then
        for i, v in pairs(model:GetDescendants()) do
            if v:IsA("JointInstance") then
                local save = false
                if (v.Part0 == torso) and (v.Part1 == head) then
                    save = true
                end
                if (v.Part0 == head) and (v.Part1 == torso) then
                    save = true
                end
                if save then
                    if hedafterneck then
                        hedafterneck = v
                    end
                else
                    v:Destroy()
                end
            end
        end
    end
    if method == 3 then
        task.delay(loadtime, pcall, model.BreakJoints, model)
    end
end

for i, v in pairs(cl:GetChildren()) do
    v.Parent = c
end
cl:Destroy()

local uncollide, noclipcon = nil, nil
if noclipAllParts then
    uncollide = function()
        if c then
            for i, v in pairs(c:GetDescendants()) do
                if v:IsA("BasePart") then
                    v.CanCollide = false
                end
            end
        else
            noclipcon:Disconnect()
        end
    end
else
    uncollide = function()
        if model then
            for i, v in pairs(model:GetDescendants()) do
                if v:IsA("BasePart") then
                    v.CanCollide = false
                end
            end
        else
            noclipcon:Disconnect()
        end
    end
end
noclipcon = stepped:Connect(uncollide)
uncollide()

for i, scr in pairs(model:GetDescendants()) do
    if (scr.ClassName == "Script") and table.find(scriptNames, scr.Name) then
        local Part0 = scr.Parent
        if Part0:IsA("BasePart") then
            for i1, scr1 in pairs(c:GetDescendants()) do
                if (scr1.ClassName == "Script") and (scr1.Name == scr.Name) and (not scr1:IsDescendantOf(model)) then
                    local Part1 = scr1.Parent
                    if (Part1.ClassName == Part0.ClassName) and (Part1.Name == Part0.Name) then
                        align(Part0, Part1)
                        scr:Destroy()
                        scr1:Destroy()
                        break
                    end
                end
            end
        end
    end
end

for i, v in pairs(c:GetDescendants()) do
    if v and v.Parent and (not v:IsDescendantOf(model)) then
        if v:IsA("Decal") then
            v.Transparency = 1
        elseif v:IsA("BasePart") then
            v.Transparency = 1
            v.Anchored = false
        elseif v:IsA("ForceField") then
            v.Visible = false
        elseif v:IsA("Sound") then
            v.Playing = false
        elseif v:IsA("BillboardGui") or v:IsA("SurfaceGui") or v:IsA("ParticleEmitter") or v:IsA("Fire") or v:IsA("Smoke") or v:IsA("Sparkles") then
            v.Enabled = false
        end
    end
end

if newanimate then
    local animate = gp(c, "Animate", "LocalScript")
    if animate then
        animate.Disabled = false
    end
end

if addtools then
    for i, v in pairs(c:GetChildren()) do
        if v:IsA("Tool") then
            v.Parent = addtools
        end
    end
end

local hum0, hum1 = model:FindFirstChildOfClass("Humanoid"), c:FindFirstChildOfClass("Humanoid")
if hum0 then
    hum0:GetPropertyChangedSignal("Parent"):Connect(function()
        if not (hum0 and hum0.Parent) then
            hum0 = nil
        end
    end)
end
if hum1 then
    hum1:GetPropertyChangedSignal("Parent"):Connect(function()
        if not (hum1 and hum1.Parent) then
            hum1 = nil
        end
    end)

    ws.CurrentCamera.CameraSubject = hum1
    local camSubCon = nil
    local function camSubFunc()
        camSubCon:Disconnect()
        if c and hum1 then
            ws.CurrentCamera.CameraSubject = hum1
        end
    end
    camSubCon = renderstepped:Connect(camSubFunc)
    if hum0 then
        hum0:GetPropertyChangedSignal("Jump"):Connect(function()
            if hum1 then
                hum1.Jump = hum0.Jump
            end
        end)
    else
        respawnrequest()
    end
end

local rb = Instance.new("BindableEvent", c)
rb.Event:Connect(function()
    rb:Destroy()
    sg:SetCore("ResetButtonCallback", true)
    if destroyhum then
        if c then c:BreakJoints() end
        return
    end
    if model and hum0 and (hum0.Health > 0) then
        model:BreakJoints()
        hum0.Health = 0
    end
    if antirespawn then
        respawnrequest()
    end
end)
sg:SetCore("ResetButtonCallback", rb)

spawn(function()
    while wait() and c do
        if hum0 and hum1 then
            hum1.Jump = hum0.Jump
        end
    end
    sg:SetCore("ResetButtonCallback", true)
end)

R15toR6 = R15toR6 and hum1 and (hum1.RigType == Enum.HumanoidRigType.R15)
if R15toR6 then
    local part = gp(c, "HumanoidRootPart", "BasePart") or gp(c, "UpperTorso", "BasePart") or gp(c, "LowerTorso", "BasePart") or gp(c, "Head", "BasePart") or c:FindFirstChildWhichIsA("BasePart")
    if part then
        local cfr = part.CFrame
        local R6parts = { 
            head = {
                Name = "Head",
                Size = v3(2, 1, 1),
                R15 = {
                    Head = 0
                }
            },
            torso = {
                Name = "Torso",
                Size = v3(2, 2, 1),
                R15 = {
                    UpperTorso = 0.2,
                    LowerTorso = -0.8
                }
            },
            root = {
                Name = "HumanoidRootPart",
                Size = v3(2, 2, 1),
                R15 = {
                    HumanoidRootPart = 0
                }
            },
            leftArm = {
                Name = "Left Arm",
                Size = v3(1, 2, 1),
                R15 = {
                    LeftHand = -0.849,
                    LeftLowerArm = -0.174,
                    LeftUpperArm = 0.415
                }
            },
            rightArm = {
                Name = "Right Arm",
                Size = v3(1, 2, 1),
                R15 = {
                    RightHand = -0.849,
                    RightLowerArm = -0.174,
                    RightUpperArm = 0.415
                }
            },
            leftLeg = {
                Name = "Left Leg",
                Size = v3(1, 2, 1),
                R15 = {
                    LeftFoot = -0.85,
                    LeftLowerLeg = -0.29,
                    LeftUpperLeg = 0.49
                }
            },
            rightLeg = {
                Name = "Right Leg",
                Size = v3(1, 2, 1),
                R15 = {
                    RightFoot = -0.85,
                    RightLowerLeg = -0.29,
                    RightUpperLeg = 0.49
                }
            }
        }
        for i, v in pairs(c:GetChildren()) do
            if v:IsA("BasePart") then
                for i1, v1 in pairs(v:GetChildren()) do
                    if v1:IsA("Motor6D") then
                        v1.Part0 = nil
                    end
                end
            end
        end
        part.Archivable = true
        for i, v in pairs(R6parts) do
            local part = part:Clone()
            part:ClearAllChildren()
            part.Name = v.Name
            part.Size = v.Size
            part.CFrame = cfr
            part.Anchored = false
            part.Transparency = 1
            part.CanCollide = false
            for i1, v1 in pairs(v.R15) do
                local R15part = gp(c, i1, "BasePart")
                local att = gp(R15part, "att1_" .. i1, "Attachment")
                if R15part then
                    local weld = Instance.new("Weld", R15part)
                    weld.Name = "Weld_" .. i1
                    weld.Part0 = part
                    weld.Part1 = R15part
                    weld.C0 = cf(0, v1, 0)
                    weld.C1 = cf(0, 0, 0)
                    R15part.Massless = true
                    R15part.Name = "R15_" .. i1
                    R15part.Parent = part
                    if att then
                        att.Parent = part
                        att.Position = v3(0, v1, 0)
                    end
                end
            end
            part.Parent = c
            R6parts[i] = part
        end
        local R6joints = {
            neck = {
                Parent = R6parts.torso,
                Name = "Neck",
                Part0 = R6parts.torso,
                Part1 = R6parts.head,
                C0 = cf(0, 1, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0),
                C1 = cf(0, -0.5, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0)
            },
            rootJoint = {
                Parent = R6parts.root,
                Name = "RootJoint" ,
                Part0 = R6parts.root,
                Part1 = R6parts.torso,
                C0 = cf(0, 0, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0),
                C1 = cf(0, 0, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0)
            },
            rightShoulder = {
                Parent = R6parts.torso,
                Name = "Right Shoulder",
                Part0 = R6parts.torso,
                Part1 = R6parts.rightArm,
                C0 = cf(1, 0.5, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0),
                C1 = cf(-0.5, 0.5, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            },
            leftShoulder = {
                Parent = R6parts.torso,
                Name = "Left Shoulder",
                Part0 = R6parts.torso,
                Part1 = R6parts.leftArm,
                C0 = cf(-1, 0.5, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0),
                C1 = cf(0.5, 0.5, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            },
            rightHip = {
                Parent = R6parts.torso,
                Name = "Right Hip",
                Part0 = R6parts.torso,
                Part1 = R6parts.rightLeg,
                C0 = cf(1, -1, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0),
                C1 = cf(0.5, 1, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0)
            },
            leftHip = {
                Parent = R6parts.torso,
                Name = "Left Hip" ,
                Part0 = R6parts.torso,
                Part1 = R6parts.leftLeg,
                C0 = cf(-1, -1, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0),
                C1 = cf(-0.5, 1, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0)
            }
        }
        for i, v in pairs(R6joints) do
            local joint = Instance.new("Motor6D")
            for prop, val in pairs(v) do
                joint[prop] = val
            end
            R6joints[i] = joint
        end
        if hum1 then
            hum1.RigType = Enum.HumanoidRigType.R6
            hum1.HipHeight = 0
        end
    end
end

local torso1 = torso
torso = gp(c, "Torso", "BasePart") or ((not R15toR6) and gp(c, torso.Name, "BasePart"))
if (typeof(hedafterneck) == "Instance") and head and torso and torso1 then
    local conNeck = nil
    local conTorso = nil
    local contorso1 = nil
    local aligns = {}
    local function enableAligns()
        conNeck:Disconnect()
        conTorso:Disconnect()
        conTorso1:Disconnect()
        for i, v in pairs(aligns) do
            v.Enabled = true
        end
    end
    conNeck = hedafterneck.Changed:Connect(function(prop)
        if table.find({"Part0", "Part1", "Parent"}, prop) then
            enableAligns()
        end
    end)
    conTorso = torso:GetPropertyChangedSignal("Parent"):Connect(enableAligns)
    conTorso1 = torso1:GetPropertyChangedSignal("Parent"):Connect(enableAligns)
    for i, v in pairs(head:GetDescendants()) do
        if v:IsA("AlignPosition") or v:IsA("AlignOrientation") then
            i = tostring(i)
            aligns[i] = v
            v:GetPropertyChangedSignal("Parent"):Connect(function()
                aligns[i] = nil
            end)
            v.Enabled = false
        end
    end
end

local flingpart0 = gp(model, flingpart, "BasePart") or gp(gp(model, flingpart, "Accessory"), "Handle", "BasePart")
local flingpart1 = gp(c, flingpart, "BasePart") or gp(gp(c, flingpart, "Accessory"), "Handle", "BasePart")

local fling = function() end
if flingpart0 and flingpart1 then
    flingpart0:GetPropertyChangedSignal("Parent"):Connect(function()
        if not (flingpart0 and flingpart0.Parent) then
            flingpart0 = nil
            fling = function() end
        end
    end)
    flingpart0.Archivable = true
    flingpart1:GetPropertyChangedSignal("Parent"):Connect(function()
        if not (flingpart1 and flingpart1.Parent) then
            flingpart1 = nil
            fling = function() end
        end
    end)
    local att0 = gp(flingpart0, "att0_" .. flingpart0.Name, "Attachment")
    local att1 = gp(flingpart1, "att1_" .. flingpart1.Name, "Attachment")
    if att0 and att1 then
        att0:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (att0 and att0.Parent) then
                att0 = nil
                fling = function() end
            end
        end)
        att1:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (att1 and att1.Parent) then
                att1 = nil
                fling = function() end
            end
        end)
        local lastfling = nil
        local mouse = lp:GetMouse()
        fling = function(target, duration, rotVelocity)
            if typeof(target) == "Instance" then
                if target:IsA("BasePart") then
                    target = target.Position
                elseif target:IsA("Model") then
                    target = gp(target, "HumanoidRootPart", "BasePart") or gp(target, "Torso", "BasePart") or gp(target, "UpperTorso", "BasePart") or target:FindFirstChildWhichIsA("BasePart")
                    if target then
                        target = target.Position
                    else
                        return
                    end
                elseif target:IsA("Humanoid") then
                    target = target.Parent
                    if not (target and target:IsA("Model")) then
                        return
                    end
                    target = gp(target, "HumanoidRootPart", "BasePart") or gp(target, "Torso", "BasePart") or gp(target, "UpperTorso", "BasePart") or target:FindFirstChildWhichIsA("BasePart")
                    if target then
                        target = target.Position
                    else
                        return
                    end
                else
                    return
                end
            elseif typeof(target) == "CFrame" then
                target = target.Position
            elseif typeof(target) ~= "Vector3" then
                target = mouse.Hit
                if target then
                    target = target.Position
                else
                    return
                end
            end
            if target.Y < ws.FallenPartsDestroyHeight + 5 then
                target = v3(target.X, ws.FallenPartsDestroyHeight + 5, target.Z)
            end
            lastfling = target
            if type(duration) ~= "number" then
                duration = tonumber(duration) or 0.5
            end
            if typeof(rotVelocity) ~= "Vector3" then
                rotVelocity = v3(20000, 20000, 20000)
            end
            if not (target and flingpart0 and flingpart1 and att0 and att1) then
                return
            end
            local flingpart = flingpart0:Clone()
            flingpart.Transparency = 1
            flingpart.CanCollide = false
            flingpart.Name = "flingpart_" .. flingpart0.Name
            flingpart.Anchored = true
            flingpart.Velocity = v3_0
            flingpart.RotVelocity = v3_0
            flingpart.Position = target
            flingpart:GetPropertyChangedSignal("Parent"):Connect(function()
                if not (flingpart and flingpart.Parent) then
                    flingpart = nil
                end
            end)
            flingpart.Parent = flingpart1
            if flingpart0.Transparency > 0.5 then
                flingpart0.Transparency = 0.5
            end
            att1.Parent = flingpart
            local con = nil
            local rotchg = v3(0, rotVelocity.Unit.Y * -1000, 0)
            con = heartbeat:Connect(function(delta)
                if target and (lastfling == target) and flingpart and flingpart0 and flingpart1 and att0 and att1 then
                    flingpart.Orientation += rotchg * delta
                    flingpart0.RotVelocity = rotVelocity
                else
                    con:Disconnect()
                end
            end)
            if alignmode ~= 4 then
                local con = nil
                con = renderstepped:Connect(function()
                    if flingpart0 and target then
                        flingpart0.RotVelocity = v3_0
                    else
                        con:Disconnect()
                    end
                end)
            end
            wait(duration)
            if lastfling ~= target then
                if flingpart then
                    if att1 and (att1.Parent == flingpart) then
                        att1.Parent = flingpart1
                    end
                    flingpart:Destroy()
                end
                return
            end
            target = nil
            if not (flingpart and flingpart0 and flingpart1 and att0 and att1) then
                return
            end
            flingpart0.RotVelocity = v3_0
            att1.Parent = flingpart1
            if flingpart then
                flingpart:Destroy()
            end
        end
    end
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
local Section = Tab:NewSection("Bat")
Section:NewButton("Execute", "ButtonInfo", function()
    --Hat Required: roblox.com/catalog/7063113820/Aluminium-Baseball-Bat
clickfling = false -- set this to false if u dont want click fling or use torso fling

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

a=game.Players.LocalPlayer b=game.Players.LocalPlayer.Character c={}d=table.insert e=false for D,E in next,game:GetService("Players").LocalPlayer.Character:GetDescendants()do if E:IsA("BasePart")then d(c,game:GetService("RunService").Heartbeat:connect(function()pcall(function()E.Velocity=Vector3.new(-30,0,0)sethiddenproperty(game.Players.LocalPlayer,"MaximumSimulationRadius",math.huge)sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",999999999)game.Players.LocalPlayer.ReplicationFocus=workspace end)end))end end function f(D,E,F)game.StarterGui:SetCore("SendNotification",{Title=D;Text=E;Duration=F or 5;})end local x=game:GetService("RunService")g=Instance.new('Folder',b)g.Name='CWExtra'b.Archivable=true local y=b:Clone()y.Name='NexoPD'for D,E in next,y:GetDescendants()do if E:IsA('BasePart')or E:IsA('Decal')then E.Transparency=1 end end h=5.65 a.Character=nil a.Character=b b.Humanoid.AutoRotate=false b.Humanoid.WalkSpeed=0 b.Humanoid.JumpPower=0 b.Torso.Anchored=true f('FE Bat by Kasy','Loading...\nPlease wait '..h..' seconds.')wait(h)b.Torso.Anchored=false f('FE Bat by Kasy','Loaded..')b.Humanoid.Health=0 y.Animate.Disabled=true y.Parent=g y.HumanoidRootPart.CFrame=b.HumanoidRootPart.CFrame*CFrame.new(0,5,0)function i(D,E,F,G)Instance.new("Attachment",D)Instance.new("AlignPosition",D)Instance.new("AlignOrientation",D)Instance.new("Attachment",E)D.Attachment.Name=D.Name E.Attachment.Name=D.Name D.AlignPosition.Attachment0=D[D.Name]D.AlignOrientation.Attachment0=D[D.Name]D.AlignPosition.Attachment1=E[D.Name]D.AlignOrientation.Attachment1=E[D.Name]E[D.Name].Position=F or Vector3.new()D[D.Name].Orientation=G or Vector3.new()D.AlignPosition.MaxForce=999999999 D.AlignPosition.MaxVelocity=math.huge D.AlignPosition.ReactionForceEnabled=false D.AlignPosition.Responsiveness=math.huge D.AlignOrientation.Responsiveness=math.huge D.AlignPosition.RigidityEnabled=false D.AlignOrientation.MaxTorque=999999999 D.Massless=true end function j(D,E,F)Instance.new("Attachment",D)Instance.new("AlignPosition",D)Instance.new("Attachment",E)D.Attachment.Name=D.Name E.Attachment.Name=D.Name D.AlignPosition.Attachment0=D[D.Name]D.AlignPosition.Attachment1=E[D.Name]E[D.Name].Position=F or Vector3.new()D.AlignPosition.MaxForce=999999999 D.AlignPosition.MaxVelocity=math.huge D.AlignPosition.ReactionForceEnabled=false D.AlignPosition.Responsiveness=math.huge D.Massless=true end for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then d(c,x.RenderStepped:Connect(function()E.CanCollide=false end))end end for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then d(c,x.Stepped:Connect(function()E.CanCollide=false end))end end for D,E in next,y:GetDescendants()do if E:IsA('BasePart')then d(c,x.RenderStepped:Connect(function()E.CanCollide=false end))end end for D,E in next,y:GetDescendants()do if E:IsA('BasePart')then d(c,x.Stepped:Connect(function()E.CanCollide=false end))end end for D,E in next,b:GetDescendants()do if E:IsA('Accessory')then i(E.Handle,y[E.Name].Handle)end end i(b['Head'],y['Head'])i(b['Torso'],y['Torso'])j(b['HumanoidRootPart'],y['Torso'],Vector3.new(0,0,0))i(b['Right Arm'],y['Right Arm'])i(b['Left Arm'],y['Left Arm'])i(b['Right Leg'],y['Right Leg'])i(b['Left Leg'],y['Left Leg'])k=a:GetMouse()local z=Instance.new("Part",g)z.CanCollide=false z.Transparency=1 d(c,x.RenderStepped:Connect(function()local D=workspace.CurrentCamera.CFrame.lookVector local E=y["HumanoidRootPart"]z.Position=E.Position z.CFrame=CFrame.new(z.Position,Vector3.new(D.X*10000,D.Y,D.Z*10000))end))l=false m=false n=false o=false p=false function q(D)r=Instance.new('BodyAngularVelocity',D)r.AngularVelocity=Vector3.new(9e9,9e9,9e9)r.MaxTorque=Vector3.new(9e9,9e9,9e9)end q(b.HumanoidRootPart)k=a:GetMouse()s=Instance.new('BodyPosition',b.HumanoidRootPart)s.P=9e9 s.D=9e9 s.MaxForce=Vector3.new(99999,99999,99999)local A d(c,x.Heartbeat:Connect(function()if A==true then s.Position=k.Hit.p b.HumanoidRootPart.Position=k.Hit.p else s.Position=y.Torso.Position b.HumanoidRootPart.Position=y.Torso.Position end end))local B=Instance.new("SelectionBox")B.Adornee=b.HumanoidRootPart B.LineThickness=0.02 B.Color3=Color3.fromRGB(250,0,0)B.Parent=b.HumanoidRootPart B.Name="RAINBOW"t=B if clickfling then d(c,k.Button1Down:Connect(function()A=true end))d(c,k.Button1Up:Connect(function()A=false end))end d(c,k.KeyDown:Connect(function(D)if D==' 'then p=true end if D=='w'then l=true end if D=='s'then m=true end if D=='a'then n=true end if D=='d'then o=true end end))d(c,k.KeyUp:Connect(function(D)if D==' 'then p=false end if D=='w'then l=false end if D=='s'then m=false end if D=='a'then n=false end if D=='d'then o=false end end))local function C(D,E,F)z.CFrame=z.CFrame*CFrame.new(-D,E,-F)y.Humanoid.WalkToPoint=z.Position end d(c,x.RenderStepped:Connect(function()if l==true then C(0,0,1e4)end if m==true then C(0,0,-1e4)end if n==true then C(1e4,0,0)end if o==true then C(-1e4,0,0)end if p==true then y.Humanoid.Jump=true end if l~=true and n~=true and m~=true and o~=true then y.Humanoid.WalkToPoint=y.HumanoidRootPart.Position end end))workspace.CurrentCamera.CameraSubject=y.Humanoid u=Instance.new('BindableEvent')d(c,u.Event:Connect(function()y:Destroy()e=true v=false for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then E.Anchored=true end end w=b.Humanoid:Clone()b.Humanoid:Destroy()w.Parent=b game.Players:Chat('-re')for D,E in pairs(c)do E:Disconnect()end game:GetService("StarterGui"):SetCore("ResetButtonCallback",true)u:Remove()end))game:GetService("StarterGui"):SetCore("ResetButtonCallback",u)

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
reanim.Humanoid.WalkSpeed = 16
mousechanger=game.Players.LocalPlayer:GetMouse().KeyDown:Connect(function(k)
if k == 'q' then-- first mode
Mode='1'
reanim.Humanoid.WalkSpeed = 16
elseif k == 'e' then-- second mode
Mode='2'
end
end)

attacklol=game.Players.LocalPlayer:GetMouse().Button1Down:Connect(function()
Mode='Attack1'
wait(0.1) -- time of attack u can edit this
Mode='Attack2'
wait(0.1)
Mode='Attack3'
wait(0.3)
Mode ='2' -- change this mode to whatever u want the mode to be after attacking
end)
hat('Aluminium Baseball Bat','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),0+0*math["cos"](sine/10),-0.7+0*math["cos"](sine/10))*CFrame.Angles(math.rad(0+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(-25+0*math["cos"](sine/10))),false)
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
reanim.Humanoid.WalkSpeed = 16
if Root.Velocity.y > 1 then -- jump
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(20+0*math.cos(sine/10)),math.rad(45+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-20+0*math.cos(sine/10)),math.rad(-45+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-1+0*math.cos(sine/10))*CFrame.Angles(math.rad(-20+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-1+0*math.cos(sine/10))*CFrame.Angles(math.rad(-15+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Aluminium Baseball Bat','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),0+0*math["cos"](sine/10),-0.7+0*math["cos"](sine/10))*CFrame.Angles(math.rad(0+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(-25+0*math["cos"](sine/10))),false)
elseif Root.Velocity.y < -1 then -- fall
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(20+0*math.cos(sine/10)),math.rad(45+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-20+0*math.cos(sine/10)),math.rad(-45+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-1+0*math.cos(sine/10))*CFrame.Angles(math.rad(-20+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-1+0*math.cos(sine/10))*CFrame.Angles(math.rad(-15+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Aluminium Baseball Bat','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),0+0*math["cos"](sine/10),-0.7+0*math["cos"](sine/10))*CFrame.Angles(math.rad(0+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(-25+0*math["cos"](sine/10))),false)
elseif Root.Velocity.Magnitude < 2 then -- idle
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.05*math.sin(sine/50),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.05*math.sin(sine/50),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.05*math.sin(sine/50),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.05*math.sin(sine/50),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.05*math.sin(sine/50),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Aluminium Baseball Bat','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),0+0*math["cos"](sine/10),-0.7+0*math["cos"](sine/10))*CFrame.Angles(math.rad(0+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(-25+0*math["cos"](sine/10))),false)
elseif Root.Velocity.Magnitude > 20 then -- run

elseif Root.Velocity.Magnitude < 20 then -- walk
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.1+-0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-10+0*math.cos(sine/20)),math.rad(0+5*math.cos(sine/20)),math.rad(0+5*math.cos(sine/20))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+-60*math.cos(sine/20)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+60*math.cos(sine/20)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/20),-1+-0.2*math.sin(sine/20),0+-0.3*math.cos(sine/20))*CFrame.Angles(math.rad(0+60*math.cos(sine/20)),math.rad(0+0*math.cos(sine/20)),math.rad(0+0*math.cos(sine/20))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/20),-1+0.2*math.sin(sine/20),0+0.3*math.cos(sine/20))*CFrame.Angles(math.rad(10+-60*math.cos(sine/20)),math.rad(0+0*math.cos(sine/20)),math.rad(0+0*math.cos(sine/20))),.2)
hat('Aluminium Baseball Bat','Torso',CFrame.new(0,0,0),CFrame.new(0+0*math["cos"](sine/10),0+0*math["cos"](sine/10),-0.7+0*math["cos"](sine/10))*CFrame.Angles(math.rad(0+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10)),math.rad(-25+0*math["cos"](sine/10))),false)
end

elseif Mode == '2' then
reanim.Humanoid.WalkSpeed = 35
if Root.Velocity.y > 1 then -- jump
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(20+0*math.cos(sine/10)),math.rad(45+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-20+0*math.cos(sine/10)),math.rad(-45+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-1+0*math.cos(sine/10))*CFrame.Angles(math.rad(-20+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-1+0*math.cos(sine/10))*CFrame.Angles(math.rad(-15+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Aluminium Baseball Bat','Right Arm',CFrame.new(0,0,0),CFrame.new(0.9+0*math["cos"](sine/10),0.7+0*math["cos"](sine/10),-1+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-90+0*math["cos"](sine/10)),math.rad(45+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
elseif Root.Velocity.y < -1 then -- fall
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(20+0*math.cos(sine/10)),math.rad(45+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-20+0*math.cos(sine/10)),math.rad(-45+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-1+0*math.cos(sine/10))*CFrame.Angles(math.rad(-20+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),0+0*math.cos(sine/10),-1+0*math.cos(sine/10))*CFrame.Angles(math.rad(-15+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Aluminium Baseball Bat','Right Arm',CFrame.new(0,0,0),CFrame.new(0.9+0*math["cos"](sine/10),0.7+0*math["cos"](sine/10),-1+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-90+0*math["cos"](sine/10)),math.rad(45+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
elseif Root.Velocity.Magnitude < 2 then -- idle
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.05*math.sin(sine/50),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1+0*math.cos(sine/10),0+0.05*math.sin(sine/50),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(100+0*math.cos(sine/10)),math.rad(13.23+0*math.cos(sine/10)),math.rad(-24.98+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-0.14+0*math.cos(sine/10),-0.14+0.05*math.sin(sine/50),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(90+0*math.cos(sine/10)),math.rad(20.87+0*math.cos(sine/10)),math.rad(13.23+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+-0.05*math.sin(sine/50),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+-0.05*math.sin(sine/50),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Aluminium Baseball Bat','Right Arm',CFrame.new(0,0,0),CFrame.new(0.9+0*math["cos"](sine/10),0.7+0*math["cos"](sine/10),-1+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-90+0*math["cos"](sine/10)),math.rad(45+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
elseif Root.Velocity.Magnitude > 20 then -- run
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.1*math.sin(sine/7.5),0+0*math.cos(sine/7.5))*CFrame.Angles(math.rad(-17.34+0*math.cos(sine/7.5)),math.rad(0+0*math.cos(sine/7.5)),math.rad(0+0*math.cos(sine/7.5))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1+0*math.cos(sine/10),0+0.1*math.sin(sine/7.5),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(50+0*math.cos(sine/10)),math.rad(13.23+0*math.cos(sine/10)),math.rad(-24.98+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-0.14+0*math.cos(sine/10),-0.14+0.1*math.sin(sine/7.5),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(50+0*math.cos(sine/10)),math.rad(20.87+0*math.cos(sine/10)),math.rad(13.23+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/15),-1+-0.2*math.sin(sine/15),0+-0.5*math.cos(sine/15))*CFrame.Angles(math.rad(0+60*math.cos(sine/15)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/15),-1+0.2*math.sin(sine/15),0+0.4*math.cos(sine/15))*CFrame.Angles(math.rad(0+-60*math.cos(sine/15)),math.rad(0+0*math.cos(sine/15)),math.rad(0+0*math.cos(sine/10))),.2)
hat('Aluminium Baseball Bat','Right Arm',CFrame.new(0,0,0),CFrame.new(0.9+0*math["cos"](sine/10),0.7+0*math["cos"](sine/10),-1+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-90+0*math["cos"](sine/10)),math.rad(45+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
elseif Root.Velocity.Magnitude < 20 then -- walk

end

elseif Mode == 'Attack1' then --attack clerp 
hat('Aluminium Baseball Bat','Right Arm',CFrame.new(0,0,0),CFrame.new(0.9+0*math["cos"](sine/10),0.7+0*math["cos"](sine/10),-1+0*math["cos"](sine/10))*CFrame.Angles(math.rad(-90+0*math["cos"](sine/10)),math.rad(45+0*math["cos"](sine/10)),math.rad(0+0*math["cos"](sine/10))),false)
RS.C0=RS.C0:Lerp(CFrame.new(1+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(120+0*math.cos(sine/10)),math.rad(-35+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0.25+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(90+0*math.cos(sine/10)),math.rad(-15+0*math.cos(sine/10)),math.rad(45+0*math.cos(sine/10))),.2) 
elseif Mode == 'Attack2' then --attack clerp 
RS.C0=RS.C0:Lerp(CFrame.new(1+0*math.cos(sine/10),-0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(120+0*math.cos(sine/10)),math.rad(-90+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0.25+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(90+0*math.cos(sine/10)),math.rad(-2.06+0*math.cos(sine/10)),math.rad(45+0*math.cos(sine/10))),.2) 
elseif Mode == 'Attack3' then --attack clerp 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-10+0*math.cos(sine/10)),math.rad(20+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0+0*math.cos(sine/10),-0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(188.99+0*math.cos(sine/10)),math.rad(-193.1+0*math.cos(sine/10)),math.rad(97.29+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1+0*math.cos(sine/10),0+0*math.cos(sine/10),0.5+0*math.cos(sine/10))*CFrame.Angles(math.rad(89.64+0*math.cos(sine/10)),math.rad(13.23+0*math.cos(sine/10)),math.rad(-32.62+0*math.cos(sine/10))),.2) 
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
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ProjectXHUB/Kram-life-Taleport-BY-Project-x-hub/main/README.md"))()
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

local Tab = Window:NewTab("COMBAT WARRIORS")
local Section = Tab:NewSection("Project Hook Hub")
Section:NewButton("Execute", "ButtonInfo", function()
    loadstring(game:HttpGet("https://projecthook.xyz/scripts/free.lua"))()
end)
