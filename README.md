# BackpackFedd
# #####Locations ###############
Location.create(name:"New York" , country:'USA')
Location.create(name:"Miami" , country:'USA')
Location.create(name:"Mexico" , country:'MX')
Location.create(name:"Cabarete", country:'DR')
###############New York
Activity.create(location_id:1, name:"Cascade Mountain", description:'Cascade Mountain and Porter Mountain are two of the more moderate peaks, making them readily accessible to hikers of various abilities. Taking the 5.5-mile Cascade Mountain Trail allows you to enjoy both of these peaks, panoramic views, a flowing river, some easy rock scrambles, and even a waterfall.', category:'hiking', state:"Lake Placid", directions:'Keene, Nueva York 12942')
Activity.create(location_id:1, name:"Devil’s Hole Trail", description:'The Devil’s Hole Trail runs along the river with amazing views of steep Niagara Gorge, bubbling white water rapids, and the Devil’s Hole itself, an impressively large whirlpool that can become mesmerizing to watch', category:'hiking', state:"Niagara Falls", directions:'Niagara Scenic Pkwy, Niagara Falls, NY 14305')
Activity.create(location_id:1, name:"Robert H. Treman State Park", description:'The trail passes by a dozen different waterfalls, including the incredible 115-foot Lucifer Falls and the 70-foot Lower Falls. The jagged glacial stone adds dimension and interest to the other impressive natural features in this gorgeous wooded ravine', category:'hiking', state:"Cancun", directions:'112 E Buttermilk Falls Rd, Ithaca, NY 14850')
Activity.create(location_id:1, name:"Stairway To Heaven", description:'The Stairway to Heaven Trail (what locals call the Stairway Ridge Trail) is full of fun and activity for those looking for something different and a good workout', category:'hiking', state:"Wilmington", directions:'Wilmington, Nueva York 12997')
Activity.create(location_id:1, name:"Bear Mountain State Park", description:'The Appalachian Trail even has a presence here. Some of the most popular trails are the Bear Mountain Loop, the Major Welch Trail, the Dunderberg Spiral Railway, and the Bald Mountain Loop.', category:'hiking', state:"Bear Mountain", directions:'Highlands, Nueva York 10986')


Activity.create(location_id:1, name:"Hither Hills", description:"Located at the eastern end of Long Island's South Fork, near the hamlet of Montauk, Hither Hills State Park is a dramatically beautiful combination of ocean, bay, lake and woodlands", category:'camping', state:"Long Island", directions:'164 Old Montauk Hwy, Montauk, NY 11954')
Activity.create(location_id:1, name:"Fish Creek Pond", description:" Fish Creek Pond Campground offers a natural sand shoreline and water access for most campsites", category:'camping', state:"Albany", directions:'4523 NY-30, Saranac Lake, NY 12983')
Activity.create(location_id:1, name:"North-South Lake", description:" North-South Lake is the biggest and most popular state campground in the Catskill Forest Preserve, offering extraordinary scenic beauty", category:'camping', state:"New York", directions:'874 N Lake Rd, Haines Falls, NY 12436')


Activity.create(location_id:1, name:"DUMBO", description:"Dumbo’s name is an acronym for Down Under the Manhattan Bridge Overpass, and the span gives the creatively oriented neighborhood much of its character—as do cobblestone streets and dramatic architecture left over from its industrial day", category:'touring', state:"Brooklyn", directions:'DUMBO, Brooklyn, Nueva York 11201')
Activity.create(location_id:1, name:"Central Park", description:"Main attractions include landscapes such as the Ramble and Lake, Hallett Nature Sanctuary, the Jacqueline Kennedy Onassis Reservoir, and Sheep Meadow; amusement attractions such as Wollman Rink, Central Park Carousel, and the Central Park Zoo; formal spaces such as the Central Park Mall and Bethesda Terrace; and the Delacorte Theater.", category:'touring', state:"Manhattan", directions:'Central Park, New York, NY')
Activity.create(location_id:1, name:"Coney Island", description:"Coney Island is a New York City neighborhood that features an amusement area that includes 50 or more separate rides and attractions", category:'touring', state:"Brooklyn", directions:'Brooklyn, Nueva York')


Activity.create(location_id:1, name:"Floating Pool", description:"Even on the hottest summer days, this particular body of water simply isn’t appealing to anyone who values personal hygiene.", category:'swimming', state:"Bronx", directions:'Bronx')

Activity.create(location_id:1, name:"Hudson Smokehouse", description:"the range of barbecue styles it presents on its playful menu, but also because of its dedication to extensively smoking the meat using lots of wood", category:'eating', state:"Manhattan", directions:'498 9th Ave New York, NY 10018 (646) 863-2020')
Activity.create(location_id:1, name:"Farida", description:"Farida focuses its bill of fare on the delicious and diverse foodways of Central Asia", category:'eating', state:"Bronx", directions:'37 Bruckner Blvd Bronx, NY 10454')




###############Florida
Activity.create(location_id:2, name:"Lummus Park", description:'Celebrities run along the pristine tan sand, and rollerbladers wind their way along the paved beachside path.', category:'swimming', state:"Miami", directions:'1130 Ocean Dr, Miami Beach, FL 33139')
Activity.create(location_id:2, name:"Bal Harbour Beach", description:'Head to Bal Harbour beach. Sandwiched between Sunny Isles Beach (to the north) and Surfside (to the south)', category:'swimming', state:"Florida", directions:'Florida 33154')
Activity.create(location_id:2, name:"South Beach", description:"It's the spot where Art Deco architecture meets high-end modern design. It's the site of some of the city's best restaurants, coolest galleries, and most vibrant nightlife.", category:'swimming', state:"Miami Beach", directions:'Miami Beach, Florida 33139')
Activity.create(location_id:2, name:"Crandon Park", description:"The turquoise waters are translucent, calm, and shallow, making them a perfect spot for families to splash about", category:'swimming', state:"Miami Beach", directions:'Miami Beach, Florida 33139')


Activity.create(location_id:2, name:"OLD CUTLER TRAIL", description:"Starting in Coco Plum, this historical trail comes out to a little over 13 miles total. Walk along one of the city’s oldest roads and veer into the many natural escapes along the way like Matheson Hammock and Fairchild Tropical Garden.", category:'walking', state:"Miami Beach", directions:'Miami Beach, Florida 33139')
Activity.create(location_id:2, name:"THE VENETIAN CAUSEWAY", description:"Did you know that there are 11 Venetian Islands? Thanks to this bridge built in 1927, you can wind and weave along this 12-bridge path and explore the many beautiful houses, breathtaking bay views, and connect downtown to Miami Beach.", category:'walking', state:"Miami Beach", directions:'Miami Beach, Florida 33139')
Activity.create(location_id:2, name:"MIAMI RIVERWALK", description:"The Miami River is possibly one of the least admired landmarks that this city has to offer and the Miami", category:'walking', state:"Miami Beach", directions:'Miami Beach, Florida 33139')

############# UserCreate #########
User.create(name:"Carlos", last_name:'Polanco', email:'carlos@email.com', phone:"999-999-9999", password:"carlosPass", swimming:true, hiking:true, walking:true, eating:true, touring:true , camping:true)
User.create(name:"Jeff", last_name:'Bezos', email:'Jeff@email.com', phone:"999-999-9999", password:"jeffPass", swimming:false, hiking:true, walking:true, eating:false, touring:true , camping:true)


# #####UserActivities
UserActivity.create(user_id:1, activity_id:1 , date:'8/5/2022')
UserActivity.create(user_id:1, activity_id:2 , date:'8/5/2022')
UserActivity.create(user_id:2, activity_id:3 , date:'7/4/2022')
UserActivity.create(user_id:2, activity_id:4 , date:'7/4/2022')


###############ActivityReview
ActivityReview.create(activity_id:1,  user_id:1, comment:'Amazing place')
ActivityReview.create(activity_id:2,  user_id:1, comment:'Incredible place')



################UserFriends
UserFriend.create(user_id:1, friend_id:2)
UserFriend.create(user_id:2, friend_id:1)



########### FriendsGoing
FriendsGoing.create(user_activity_id:1 , user_friend_id:1)


###############
ChatRoom.create(user_id:1 , user_id2:2)

Message.create(chat_room_id:1 , user_id:1 , message:'KLK Bezos')
Message.create(chat_room_id:1 , user_id:2 , message:'KLK Manito')
Message.create(chat_room_id:1 , user_id:2 , message:'Aqui en el Espacio')
