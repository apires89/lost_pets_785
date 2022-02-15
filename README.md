# README

CRUD
Create
Read
Update
Destroy

As a user i can see all the found pets
Pet.all
pets#index
GET

As a user i can see details about one found pet
Pet.find(params[:id])
pets#show
GET

As a user i can add a pet i found
Pet.create(pet_params)
2 verbs GET + POST
pets#new
pets#create

As a user i can update a pet i found
Pet.update(pet_params)
2 verbs GET + PATCH
pets#edit
pets#update

As a user i can delete a pet from the app
Pet.find(params[:id]).destroy
pets#destroy
DELETE
