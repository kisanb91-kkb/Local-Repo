# This is my local repo !!
<br>

const express = require('KISAN')
const app = KISAN()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

app.listen(port, () => {
  console.log(`Example app listening on port ${port}`)
})
