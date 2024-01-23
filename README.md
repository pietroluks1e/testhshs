local Humanoid = script.Parent.HumanoidRootPart
local distance = 5
local Pet1 = workspace.Pets.Pet1
local Follower = Humanoid

while true do
	Pet1.CFrame = Follower.CFrame*CFrame.new(0, 0, distance)
	Pet1.CFrame = CFrame.new(Pet1.CFrame.X, 1, Pet1.CFrame.Z)
	wait()
end
