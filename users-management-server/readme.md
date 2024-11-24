1. Create a post api on the server side
2. Client side send data via post
3. set fetch method inside the fetch options (second parameter)
4. options will have three things: method, haader, body
5. headers "content-type" : "application/json"
6. don't forget to send data by JSON.Stringify in the body.
7. On the server side: express.json() middleware