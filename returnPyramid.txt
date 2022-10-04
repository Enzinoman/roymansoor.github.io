function returnPyramid(height){
    var pyramid = [];
    var incrementer = 1;
    var hashtag = "";
    for(incrementer; incrementer < height+1; incrementer++){

        hashtag += '#';
        pyramid.push(hashtag);
        console.log(pyramid);
        }
    
}