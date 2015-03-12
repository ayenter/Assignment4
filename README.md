1. Briefly describe your team’s project

	•Our project is to make a website where members can post a question about decisions that they are considering. Then other members can post responses to solve the decision question. The members can also vote on the possible solutions. The solution with most votes will be considered the wining decision.  


2. Research and compile a list of APIs that might be useful for your project
3. For each API, briefly describe how its functionality might be used in your project

	•Google Plus
		- sign in
			* This will allow current and new members to log in to the website without entering any information
		- friends list
			* This will allow members to invite or interact with their friends on Google Plus
	•Facebook
		- sign in
			* This will allow current and new members to log in to the website without entering any information
		- friends list
			* This will allow members to invite or interact with their friends on Facebook
	•Twitter
		- sign in
			* This will allow current and new members to log in to the website without entering any information
		- friends list
			* This will allow members to invite or interact with their friends on Twitter
	•Google Maps
		- location displayed on map
			* If solutions involve locations, then these locations can show up on a map (ex: where should I eat? {In-n-out})
	

4. Choose one API from your list and create an example web page using jQuery AJAX to call the API and display the returned results
	
	•I use the Facebook API to create a login button and display a list of friends. This is strictly just a demonstration of using the API; it is not pretty.
	*** The problem with the Facebook thing is that it must be a registered website and only the developers can access it. Therefore, I posted the website at http://ecs.fullerton.edu/~cs431s24/fbtry1.html . However, anybody but me will be issued an error stating that the app is only available to the developers. ***


5. Describe why you chose that particular API and provide a link to its documentation

	•Everybody (except Professor Avery) uses Facebook, or at least has a Facebook page. Since our targeted users are "social" people who want to be "social" with their "social" decisions, I fugured that one of the most popular social networks would be a good place to start. This is also ideal because it allows people to be lazy enough to skip the signup/login part.


6. Discuss any potential issues that you can foresee with using this API in your project

	•Problems are that connecting to Facebook means registering with Facebook and, if the certain permissions are needed, submitting the website to Facebook for review.


7. Evaluate your experience creating the example web page and make a recommendation of whether your team should use this API or keep looking for better options
	
	•I think this is still a good piece to include in the project; however, the request for all friends means having high permissions. Therefore, I believe we should drop this and only include friends that are strictly part of the app already. A better option may be Google Plus.


8. Describe how the example you wrote might be expanded to use additional functionality provided by the API

	•Additional functionality may be implemented through getting the user's information, such as location. Therefore, if we implement Google Maps, then we can sort based on the location of the user who asked the question.
	Sudo Code Example:
		Ross: Where should we all go to eat?
		Rachel: Central Perk

		Map: {POI: {Central Perk}, NearLocation: {Ross.Facebook.getLocation}}
		show(Map)

