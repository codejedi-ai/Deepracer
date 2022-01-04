# Deepracer
 This is the repository for my deepracer reward function
AWS Deepracer is  1/18 scale race car trained in a 3D world using reinforcement learning. This reward function looked at the future state of the track and determined the optimal speed for a turn. More info in https://towardsdatascience.com/an-advanced-guide-to-aws-deepracer-2b462c37eea. I also wanted to incorperate some strategies of making a turn in the indianapolice race track video link here. https://www.khanacademy.org/science/physics/centripetal-force-and-gravitation/centripetal-acceleration-tutoria/v/jrhildebrand-turning Which basically told the agent to turn left on the right lane and turn right on the left lane to maximize the turning radius. 

I tried my best to train on the AWS trining console however finding it too expensive. (I burned over $130 on over 30 hours of training)

After reading variouse articles it was determined that the most cost efficient way to train the model was to use a graphics optimized gaming computer.

The dockers for Deepracer for cloud https://github.com/aws-deepracer-community/deepracer-for-cloud only supported nvidia I have a M1 Macbook pro.

I believe building a gaming computer during the global chip shortage was not a wise decision

After learning the rienforcement learning course by perian data, some day this project could be attempted again with concepts of deep Q-Learning and open AI gym. For now this project was put on hold.
