# twitter-connect-email
We can get the email from twitter authentication for Ionic2 framework

#install 
For these you have to download the "cordova-twitter-connect-email" , follow the how to install these new cordova plugin to the your ionic2

#usage
Just follow the "twitter-connect" plugin intructions same as here also

Use the this function to get the email from twitter authentication in ionic2.


this.twitter.showUserEmail().then(
			function (res) {
				alert(JSON.stringify(res));
        /* it will alert the some data with email address of authenticated user*/
			},
			function (error) {
				alert(JSON.stringify(error));
			}
		)
