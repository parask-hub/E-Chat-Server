# E-Chat-Server

Questions
to create question -> /api/questionRoute/addque/:userId
to update question -> /api/questionRoute/upque/:userId/:questionId
to delete question -> /api/questionRoute/delque/:userId/:questionId
to bookmaek a question -> /api/questionRoute/bookmark/:id/:questionId

Answers
to create Answer -> /api/answerRouteRoute/addans/:userId/:queId
to update Answer -> /api/answerRoute/upans/:answerId
to delete Answer -> /api/answerRoute/delans/:answerId
to post likes on a answer -> api/answerRoute/:userId/:answerId/like
to get count and name of user who likes answer -> api/answerRoute/:answerId/likes
