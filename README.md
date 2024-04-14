#File structure:

```
├── controllers
│   ├── export_controller.js
│   ├── sample_controller.js
│   └── util.js
├── package.json
├── README.md
├── routes
│   ├── dialogflow_route.js
│   └── home_route.js
└── src
    └── index.js
```

`index.js` is the entry point, which calls the `routes`, from here we call the individual `controller` for that request.


#First need to install the required packages to run the code:
> ```npm install --save```

then run the `index.js` file with either

> ```node src/index.js```

or

> ```npm start```

## Expose localhost
Install **NGROK** 

Then run

> ```ngrok http 5000```


