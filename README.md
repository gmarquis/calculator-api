docker run -p 32800:5000 virtualvessel/store:calculator-api <br>
curl -i -H "Content-Type: application/json" -X POST http://localhost:32800 <br>
/add -d '{"argument1":42, "argument2":1 }' <br>
/subtract -d '{"argument1":42, "argument2":1 }' <br>
/multiply -d '{"argument1":9, "argument2":9 }' <br>
/divide -d '{"argument1":42, "argument2":2 }' <br>
