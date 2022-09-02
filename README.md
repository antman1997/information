# information
This will only contain a readMe of important information on coding

API >>

  API's are transponders; they are used to receive requested information and sends back information depending on the request. In addition, it provides security for information being received and being sent back.

FETCH API >>

  Fetch API provides a javascript interfade for accessing and manipulating parts of the HTTP pipeline, such as requests and responses. In addition, it provides a global fetch() method that provides an easy, logical way to fetch resources asynchronously across the network.

      Fetch() method is available in the global scope that instructs the web browsers to send a request to a URL.

      Fetch() requires only one parameter which is the URL of the resource that you want to fetch
          example : let response = fetch(url);

      Fetch() method returns a PROMISE so you can use the then() and the catch() methods can handle it
          example : .then(response => {
                        // handle the response
                    })
                    .catch(error => {
                        // handle the error
                    })

      PROMISE >>
        The promise object represents the eventual completion (or failure) of an asynchronous operation and its resulting value (so basically the promise object the process before the+ response). 3 possible states, fulfilled, rejected, or pending.
