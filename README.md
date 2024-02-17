Description: Airbnb clone is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB.

The project currently only implements the back-end console.

Classes: AirBnB utilizes the following classes:

BaseModel FileStorage User State City Amenity Place Review PUBLIC INSTANCE ATTRIBUTES id created_at updated_at Inherits from BaseModel Inherits from BaseModel Inherits from BaseModel Inherits from BaseModel Inherits from BaseModel Inherits from BaseModel PUBLIC INSTANCE METHODS save to_dict all new save reload "" "" "" "" "" "" PUBLIC CLASS ATTRIBUTES email password first_name last_name name state_id name name city_id user_id name description number_rooms number_bathrooms max_guest price_by_night latitude longitude amenity_ids place_id user_id text PRIVATE CLASS ATTRIBUTES file_path objects Storage 🛄 The above classes are handled by the abstracted storage engine defined in the FileStorage class.

