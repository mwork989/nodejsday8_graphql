# # specific user and companyd details schema
# {
#   user(id:"23"){
#     id,
#     firstName,
#     age
#   }
# }

# specific user and companyd details schema_bk
# {
#   user(id:"23"){
#     id,
#     firstName,
#     age,
#     company{
# 			name,
# 			location
# 			}
#   }
# }


# list of uses working in company  schema_bk
# {
#   company(id:"2"){
#     name,
#     location,
#     user{
# 			firstName,
# 			age
# 			}
#   }
# }

# adding a new user 
# mutation{
#   addUser(firstName:"oriaon",age:42,companyId:"3"){
#     id,
#     firstName
#     age
#   }
# }





