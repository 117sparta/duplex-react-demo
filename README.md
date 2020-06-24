This is a demo base on [electron-react-boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate).

## Start

First, run `yarn` to install dependencies, then `cd app/` and run `yarn` to install dependencies that are required by packaging.<br />
Second, clone the [grpc-go](https://github.com/grpc/grpc-go) project. Maybe you need to configure go environment according to the [readme](https://github.com/grpc/grpc-go/tree/master/examples) of the examples. If you configure the environment successfully, you can open the `route_guide` example and run `go run server/server.go` in terminal.<br/>
Lastly, go back to this demo and run `cd ..`, `yarn dev` to start the electron app.

## Result

I guess you can see that you can get the response the first time program ping but fail always later.

## Tip

The main program is the connectServer function in `app/components/Home.tsx`.
