# graphql

* Users

query{
  users{
    name
    email
    postsCount
  }
}  
 
* User

{
  user(id:2){
    name
    email
    postsCount
    posts{
      title
      body
    }
  }
}


