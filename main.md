*{
  box-sizing: border-box;
  margin: 0;
  scroll-behavior: smooth;
}

html{
  font-size: 16px;
}


header {
  height: 100vh;
  background-color: #cfe6e8;
  color: #0d0f0f;
}



header h1 {
  font-size: 5rem;
  padding-bottom: 1rem;
}

.tagline {
  font-family: sans-serif;
  text-transform: uppercase;
  font-weight: lighter;
  padding-bottom: 1rem;
}
.header-text{
    text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: inherit;
padding:2rem;
/*   outline: red solid 1px; */
}

main{
  padding-left: 2rem;
}


.header-button {
  background-color: #4C7476; 
  color: white; 
  text-transform: uppercase;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
 
}

.header-button:hover {
  background-color: #000;
  color: white;
}


img {
  padding-top: 2rem;
}