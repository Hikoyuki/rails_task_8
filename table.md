* users
  * id:integer
  * name:string
  * image:string
  * email:string
  * encrypted_password:string
  * inquiry_id:integer

* admin
  * id:integer
  * name:string
  * encrypted_password:string

* inquiries
  * id:integer
  * title:string
  * answer_id

* inquiries_users
  * inquiry_id
  * user_id

* answers
  * id:integer
  * comment:string
  * inquiry_id

* resolve
  * user_id
  * inquiry_id
