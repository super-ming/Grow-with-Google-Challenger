# Grow-with-Google-Challenger
A repository to store my code for course quizzes and projects

/*
 * Programming Quiz: Facebook Friends (7-5)
 */

// your code goes here
var facebookProfile = {
    name: "Ming",
    friends: 562,
    messages: ["I hope that I can get into this one too!", "At first I thought it would be awesome if they had Sushi Go to play in the restaurant. Then, I realized the place is called Sushido, not go.. well it would still be nice to have."],
    postMessage: function addMessage(message){
        facebookProfile.messages.push(message);
    },
    deleteMessage: function removeMessage(index){
        facebookProfile.messages.splice(index, 1);
    },
    addFriend: function addFriends(){
        facebookProfile.friends+=1;
    },
    removeFriend: function removeFriends(){
        facebookProfile.friends-=1;
    }
}
