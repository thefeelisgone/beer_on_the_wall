# beer_on_the_wall
def bottles_on_the_wall():
    counter = 99
    repeat = True
    while repeat == True :
        if counter !=1 :
            print ("{0} bottles of beer on the wall, {0} bottles of beer".format(counter))
        elif counter == 1:
            print ("{0} bottle of beer on the wall, {0} bottle of beer".format(counter))
            
        counter=counter-1 #decrease counter by 1 because 1 beer was passed around 
        
        if counter == 0: #if 0 beer= no more beer la
            counter='no more'
            repeat=False    #how to continue to pass beer if no more beer on the wall
        print ("Take one down and pass it around, {0} bottles of beer on the wall.".format(counter))
        print () #line of spacing between verses
        
    #NO MORE BEER D: Just kidding!
    print ("{0} bottles of beer on the wall".format(counter.capitalize()), "{0} bottles of beer.".format(counter))
    print ("Go to the store and buy some more, 99 bottles of beer on the wall.") #is the 99 here allowed ): 
bottles_on_the_wall()
