* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
html,
body {
  height: 100%;
  width: 100%;
}
#main {
  width: 100%;
  height: 100vh;
  background-color: black;
}
#back {
  width: 100%;
  height: 100vh;
}
#top {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background-color: black;
}
#workingarea{
    position: relative;
    width: 80%;
    max-width: 1920px;
    height: 100vh;
    margin: 0 auto;
}

#nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    padding: 30px 0;
}

#nav img {
    height: 40px;
}

#nleft , #nright{
    display: flex;
    align-items: center;
    gap: 40px;
}


#nav a{
    color: white;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: 600;
    font-size: 13px;
    text-decoration: none;
    font-family: "gilroy";
}


#hero{
    display: flex;
    justify-content: space-between;
    position: absolute;
    top: 50%;
    left: 0;
    width: 100%;
}

#heroleft{
    min-width: 50%;
}

#heroleft .elem h1 {
    font-family: "Kajiro Bold";
    color:white;
}

#heroright{
    min-width: 25%;
    background-color: green;
}