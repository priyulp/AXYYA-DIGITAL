const express = require('express')
const app = express()

app.get('/', (req, res) => res.send('Hello world!'))
app.lisen(3000, () => console.log('seerver ready'))
