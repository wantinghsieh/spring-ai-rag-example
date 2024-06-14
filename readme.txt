demo
extension of LLM
read a book: hsieh.pdf into vectorstore.json
then ask questions using 
RestMan post request
POST http://localhost:8080/ask
request:
{
    "question": "who is steve hsieh ?"
}
response:
{
    "answer": "Steve Hsieh is the first son of Wanting Hsieh, who was born in Taiwan on May 20, 1958."
}
