
See the query i put as u said

SELECT * FROM `follow_church` WHERE ((`follower_id`=203 or `blesser_id`=203 or `favourite_id`=203) or (`follower_id`=0 and `blesser_id`=0 and `favourite_id`=0)) && `church_owner_id`=49
