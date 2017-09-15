# cli-social-network-bonus
Build a CLI social network app flatiron bonus lab

## User Stories:
 As a User, I should be able to see a list of all the other users
 
 As a User, I should be able to select another user to friend/follow

 As a User I should be able to see a list of my friends/followers

 As a User I should be able to see a list of the people that are friends with me / following me

## Implementation Notes:

 A user should have a `user.friends` or `user.followers` method that returns a collection of **User Instances**. There is no such thing as Friends Model... (friend instances are just other users)

 Since a user can have many friends, and a friend can also have many friends themselves. This is a many-to-many relationships and you will need a join table with two foreign keys.

 (This join model can be called 'friendships', 'user_followers' something like that)
