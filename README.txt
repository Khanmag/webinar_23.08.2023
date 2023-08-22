test text format

.temp_wrappper {
  flex-direction: column;
  margin: 10px auto;
  background-color: rgb(66, 66, 66);
  padding: 10px;
  border-radius: 15px;
}
.temp_btn_wrapper,
.temp_wrappper {
  display: flex;
  width: 100px;
  align-items: center;
  justify-content: space-evenly;
}
.temp_wrappper > p,
button {
  border-radius: 50%;
}
.temp_wrappper > p {
  width: 100%;
  height: 100px;
  text-align: center;
  line-height: 100px;
  vertical-align: center;
  transition-duration: 0.5s;
  color: white;
}
button {
  border: none;
  width: 30px;
  height: 30px;
  background-color: lightyellow;
}
button:active {
  transform: scale(0.95);
}
.too_coldly {
  background-color: #0000ff;
}
.coldly {
  background-color: #0099ff;
}
p.normal_temp {
  background-color: #ffff00;
  color: black;
}
.warm {
  background-color: #ff9900;
}
.hotly {
  background-color: #ff6600;
}
.too_hotly {
  background-color: #ff3300;
}
