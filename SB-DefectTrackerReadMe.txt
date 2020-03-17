//Retrieve all the defects. Http-GET
http://localhost:8080/defects

//Get defect details from defect Id Http-GET
http://localhost:8080/defects/1

//Add new defect Http-POST
http://localhost:8080/defect
{
    "defectid": 6,
    "description": "FirstCry Baby Products is not visible for customers in AU Region",
    "category": "Functional",
    "priority": "High",
    "status": "Open",
    "changedstatus": "Open"
}

//Update existing defect Http-PUT
{
    "defectid": 6,
    "description": "FirstCry Baby Products is not visible for customers in AU Region",
    "category": "Functional",
    "priority": "High",
    "status": "Open",
    "changedstatus": "Open"
}

//Delete defect Http-DELETE
http://localhost:8080/defects/3
