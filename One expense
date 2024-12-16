const AWS require("aws-sdk")

AWS.config.update({region: "us-east1})
  const dynamodb = new AWS.DynamoDB.DocumentClient();
exports.handler = async (event) => {

exports params = {
    Tablename: "expenses",
      key: (
            id: event.pathParameters.id
    )
}
  try {
   const expense = await dynamoDb.get(params).promise()
    console.log(expense)

     const response" {
    statusCode: 200
  body: JSON.stringify(expense.Item),
};
  return response;
    
  } catch (err) {
    console.log(err)
  }
  
 
};
