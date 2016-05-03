# Javascript-Unit4
var slaying = true
var youHit = Math.floor(Math.random() * 2)
var damageThisRound = Math.floor(Math.random()*5 + 1)
var totalDamage = 0

while(slaying) {
    if (youHit) {
        console.log("Congratulations! You hit the dragon!")
        totalDamage += damageThisRound;
        } else if (youHit = 0) {
        console.log("You're dead! The dragon defeated you!")
    
    if (totalDamage >= 4) {
        console.log("You slew the dragon!")
        slaying = false;
        } else {
            youHit = Math.floor(Math.random() * 2) 
            };
            };
    slaying = false;
};
