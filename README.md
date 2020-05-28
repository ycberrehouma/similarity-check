# Similarity Check
<b><h2>Restful API for similarity check using natural language processing</h2></b>
{The application includes Docker and written in Python}<br><br><b></b>

- Each user can register and create an accout <br>
- All Data information is storred in MongoDB <br>
- No need to build front-end -> it can be tested via Postman <br>
- Each User has tokens to be used to check similarity <br>
- Only Admin is allowed to add tokens to users <br>
- Using spacy to check similarity <br>
- Using bcrypt to encrypt passwords <br>

<b>The restful apis are (All POST): </b>
<br>/register/{username}/{password} (To register a user)
<br>/detect/{username}/{password}/{text1}/text2}
<br>/refill/{user-username}/{admin-password}/{number-of-token}

<br>


