
## I have a couple of issues:

1. On: routes['/comments/:id'].PUT should return a 404 response with a non-existent comment.

* the request that is received have a body with an existing comment id: 1. And if you see the database there is a comment with id: 1. So the comment actually exist....

2. On: routes['/comments/:id/upvote'].PUT should return a 200 response after a succesful upvote and send back the upvoted comment.

* My response is 200, but I dont get what the response.body should have.... I tryed with requestComment.body and requestComment.body.comment and didnt work.... I dont get what do you mean by "send back the upvoted comment".

3. On: routes['/comments/:id/downvote'].PUT should return a 200 response after a succesful downvote and send back the downvoted comment.

* Same as point 2. My response is 200, but I dont get what the response.body should have.... I tryed with requestComment.body and requestComment.body.comment and didnt work.... I dont get what do you mean by "send back the upvoted comment".

## Thanks for the reading !

PD: I delete de node_modules