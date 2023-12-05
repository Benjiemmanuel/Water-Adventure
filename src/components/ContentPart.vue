<template>
  <div class="contents-part flex mt-8 mb-8">
    <div class="one">
      <div class="flex justify-between ml-12 mr-12">
        <h2>FILTERS</h2>
        <span>Reset</span>
      </div>
      <div class="under-line ml-12 mt-2"></div>
      <div class="flex justify-between ml-12 mr-12 mt-4">
        <div>
          <h2>collections</h2>
          <ul class="drop-downOne">
            <li><a href="#">Broadway (23)</a></li>
            <li><a class="text-red-500" href="#">Water Adventures (120)</a></li>
            <li><a href="#">Adventures (67)</a></li>
            <li><a href="#">Sport Shows (35)</a></li>
            <li><a href="#">Road Tours (76)</a></li>
            <li><a href="#">Mountain & Hills (13)</a></li>
            <li>
              <u><i>+23more</i></u>
            </li>
          </ul>
        </div>
        <span><i class="fas fa-chevron-down"></i></span>
      </div>
      <div class="under-line ml-10 mt-4"></div>
      <div class="flex justify-between ml-12 mr-12 mt-4">
        <div>
          <div>
            <h2>Price Range</h2>
          </div>
        </div>
        <span><i class="fas fa-chevron-down"></i></span>
      </div>
      <div class="flex justify-between mt-4 ml-12 mr-12 text-center">
        <button class="amount">$120</button>
        <button class="amount">$855</button>
      </div>
      <div></div>
    </div>

    <div class="two">
      <div class="btn-two-container flex justify-start text-center gap-5">
        <button class="btn-two">train adven x</button>
        <button class="btn-two">value packs x</button>
        <button class="btn-two">20th dec 2016 x</button>
      </div>
      <div class="pricing-part flex justify-end gap-2 m-4 mr-12">
        <div class="flex gap-2">
          <h5>Price</h5>
          <span class="low-to-high">Low to High</span>
        </div>
        <div class="vertica-line"></div>
        <div>
          <span>High to Low</span>
        </div>
        <div class="flex gap-2">
          <h5>SORT BY</h5>
          <div class="flex gap-2">
            <span class="low-to-high">Relevance</span>
            <span><i class="fas fa-chevron-down"></i></span>
            <div class="dropdown-relevance">
              <ul>
                <li><a href="#">Newwest</a></li>
                <li><a href="#">Popularity</a></li>
                <li><a href="#">Relevance</a></li>
                <li><a href="#">Rating</a></li>
                <li><a href="#">Discount</a></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.dropdown-relevance {
  position: absolute;
  margin-top: 25px;
  left: 40;
  right: 50px;
  width: 125px;
  padding-left: 10px;
  background-color: #fff;
  border: none;
  box-shadow: 0 3px 4px rgba(0, 0, 0, 0.2);
  z-index: 1000;
  display: none;
}

.dropdown-relevance ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.dropdown-relevance li {
  padding: 10px;
  font-size: 13px;
  color: #909299;
}
/* Show the dropdown on hover */
.low-to-high:hover span,
.dropdown-relevance {
  display: block;
  cursor: pointer;
}
.drop-downOne {
  margin-top: 10px;
  font-size: 11px;
  font-weight: 600;
  color: #909299;
}
.low-to-high {
  color: red;
  font-size: 13px;
  font-weight: 600;
}
h5 {
  font-size: 14px;
  font-weight: 600;
}
.drop-downOne li {
  padding-top: 10px;
}
.pricing-part {
  align-items: center;
}
.btn-two {
  border: none;
  width: 120px;
  height: 35px;
  font-size: 13px;
  color: #909299;
  background: #eaeaec;
}
span {
  font-size: 13px;
  color: #909299;
}
h2 {
  font-size: 12px;
  font-weight: bold;
  font-family: Arial;
}
.vertica-line {
  width: 2px;
  height: 15px;
  background: #dadbdd;
}
.amount {
  background: #ffff;
  border: 1px solid #909299;
  font-size: 12px;
  width: 50px;
  padding: 2px;
  text-align: center;
}
.one {
  width: 20%;
  background-color: #fff;
  height: 300px;
}
.two {
  width: 80%;
  background: #fff;
  height: 300px;
}
.under-line {
  width: 170px;
  background: #9dadc2;
  height: 1.3px;
}
</style>
