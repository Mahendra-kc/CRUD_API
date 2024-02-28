# Project CRUD API

## MONGO DB Methods

model.findById({ id }) => fetch the single data (object) (GET)
model.findByIdAndUpdate({ id }, data) => Update the(PATCH/PUT)
model.findByIdAndDelete({ id } => ) to delete single data (DELETE)

model.find() => to create or save data into database (POST)
if we create an instance to model
let newInst = new Model(data)
newInst.save()

model.findOne({ anyfield: value }) => fetch the single data (GET)
model.findOneAndUpdate({ anyField:value}, data) => to update (PATCH/PUT)
model.findOnceAndDelete({ anyField:value }) => to delete (DELETE)

// Note We use findOne method by using any column name expect the id field 
// from  the  database table(model)
