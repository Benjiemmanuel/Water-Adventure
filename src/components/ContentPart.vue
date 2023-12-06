<template>
  <div class="contents-part flex mt-8 mb-8">
    <div class="w-1/5 bg-white h-300">
      <div class="flex justify-between ml-12 mr-12">
        <h2>FILTERS</h2>
        <span>Reset</span>
      </div>
      <div class="under-line ml-12 mt-2"></div>
      <div class="flex justify-between ml-12 mr-12 mt-4">
        <div>
          <h2>collections</h2>
          <ul class="drop-downOne mt-2 text-xs font-semibold text-gray-600">
            <li class="pt-2"><a href="#">Broadway (23)</a></li>
            <li class="pt-2">
              <a class="text-red-500" href="#">Water Adventures (120)</a>
            </li>
            <li class="pt-2"><a href="#">Adventures (67)</a></li>
            <li class="pt-2"><a href="#">Sport Shows (35)</a></li>
            <li class="pt-2"><a href="#">Road Tours (76)</a></li>
            <li class="pt-2"><a href="#">Mountain & Hills (13)</a></li>
            <li class="pt-2">
              <u><i>+23more</i></u>
            </li>
          </ul>
        </div>
        <span><i class="fas fa-chevron-down"></i></span>
      </div>
      <div class="w-170 bg-blue-400 h-px1.3 ml-10 mt-4"></div>
      <div class="flex justify-between ml-12 mr-12 mt-4">
        <div>
          <div>
            <h2>Price Range</h2>
          </div>
        </div>
        <span><i class="fas fa-chevron-down"></i></span>
      </div>
      <div class="flex justify-between mt-4 ml-12 mr-12 text-center">
        <button
          class="amount bg-white border border-gray-300 text-sm w-50 p-2 text-center"
        >
          $120
        </button>
        <button
          class="amount bg-white border border-gray-300 text-sm w-50 p-2 text-center"
        >
          $855
        </button>
      </div>
      <!-- <div></div> -->
    </div>

    <div class="w-4/5 bg-white h-300">
      <div class="btn-two-container flex justify-start text-center gap-5">
        <button class="btn-two">train adven x</button>
        <button class="btn-two">value packs x</button>
        <button class="btn-two">20th dec 2016 x</button>
      </div>
      <div class="items-center flex justify-end gap-2 m-4 mr-12">
        <div class="flex gap-2">
          <h5>Price</h5>
          <span class="low-to-high" style="color: red">Low to High</span>
        </div>
        <div class="vertica-line"></div>
        <div>
          <span>High to Low</span>
        </div>
        <div class="flex gap-2">
          <h5>SORT BY</h5>
          <div class="flex gap-2">
            <span class="text-red-500 text-sm font-semibold" style="color: red"
              >Relevance</span
            >
            <span><i class="fas fa-chevron-down"></i></span>
            <div class="dropdown-relevance">
              <ul class="list-none m-0 p-0">
                <li class="p-2 text-sm text-gray-600">
                  <a href="#">Newwest</a>
                </li>
                <li class="p-2 text-sm text-gray-600">
                  <a href="#">Popularity</a>
                </li>
                <li class="p-2 text-sm text-gray-600">
                  <a href="#">Relevance</a>
                </li>
                <li class="p-2 text-sm text-gray-600">
                  <a href="#">Rating</a>
                </li>
                <li class="p-2 text-sm text-gray-600">
                  <a href="#">Discount</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="cart">
        <div class="cart-container">
          <div>
            <img class="pics" src="../assets/water-ad.jpg" alt="" />
          </div>
          <div class="p-4">
            <div>
              <h3>COLLECTION</h3>
              <p class="mt-2">Best of Maui Tour</p>
            </div>
            <div class="flex justify-between pt-6">
              <div class="text-center flex gap-2">
                <button class="read flex justify-between text-center">
                  <span class="now-color pl-1">4.0</span>
                  <span class="now-color pr-1"
                    ><i class="fa-regular fa-star"></i
                  ></span>
                </button>
                <span>(1247 Reviews)</span>
              </div>
              <div class="text-sm" style="color: #9dadc2"><del>$150</del></div>
            </div>
            <div class="flex justify-between pt-2">
              <div class="flex gap-2 text-xs">
                <span class="percentage-icon"
                  ><i class="fa-solid fa-percent"></i
                ></span>
                <span style="color: #a7e1fb; font-size: 12px"
                  >save upto 50% off</span
                >
              </div>
              <div class="text-base" style="font-weight: 600; color: gray">
                $130
              </div>
            </div>
            <hr class="mt-4" />
            <div class="flex gap-2 mt-1">
              <span><i class="fa-solid fa-sun"></i></span>
              <span>56 people viewing now</span>
            </div>
          </div>
        </div>
        <div class="cart-container">
          <div>
            <img class="pics" src="../assets/water-ad.jpg" alt="" />
          </div>
          <div class="p-4">
            <div>
              <h3>COLLECTION</h3>
              <p class="mt-2">Best of Maui Tour</p>
            </div>
            <div class="flex justify-between pt-6">
              <div class="text-center flex gap-2">
                <button class="read flex justify-between text-center">
                  <span class="now-color pl-1">4.0</span>
                  <span class="now-color pr-1"
                    ><i class="fa-regular fa-star"></i
                  ></span>
                </button>
                <span>(1247 Reviews)</span>
              </div>
              <div class="text-sm" style="color: #9dadc2"><del>$150</del></div>
            </div>
            <div class="flex justify-between pt-2">
              <div class="flex gap-2 text-xs">
                <span class="percentage-icon"
                  ><i class="fa-solid fa-percent"></i
                ></span>
                <span style="color: #a7e1fb; font-size: 12px"
                  >save upto 50% off</span
                >
              </div>
              <div class="text-base" style="font-weight: 600; color: gray">
                $130
              </div>
            </div>
            <hr class="mt-4" />
            <div class="flex gap-2 mt-1">
              <span><i class="fa-solid fa-sun"></i></span>
              <span>56 people viewing now</span>
            </div>
          </div>
        </div>
        <div class="cart-container">
          <div>
            <img class="pics" src="../assets/water-ad.jpg" alt="" />
          </div>
          <div class="p-4">
            <div>
              <h3>COLLECTION</h3>
              <p class="mt-2">Best of Maui Tour</p>
            </div>
            <div class="flex justify-between pt-6">
              <div class="text-center flex gap-2">
                <button class="read flex justify-between text-center">
                  <span class="now-color pl-1">4.0</span>
                  <span class="now-color pr-1"
                    ><i class="fa-regular fa-star"></i
                  ></span>
                </button>
                <span>(1247 Reviews)</span>
              </div>
              <div class="text-sm" style="color: #9dadc2"><del>$150</del></div>
            </div>
            <div class="flex justify-between pt-2">
              <div class="flex gap-2 text-xs">
                <span class="percentage-icon"
                  ><i class="fa-solid fa-percent"></i
                ></span>
                <span style="color: #a7e1fb; font-size: 12px"
                  >save upto 50% off</span
                >
              </div>
              <div class="text-base" style="font-weight: 600; color: gray">
                $130
              </div>
            </div>
            <hr class="mt-4" />
            <div class="flex gap-2 mt-1">
              <span><i class="fa-solid fa-sun"></i></span>
              <span>56 people viewing now</span>
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
.now-color {
  color: #fff;
}
.percentage-icon {
  border: 1px solid #c3eafc;
  width: 15px;
  color: #c3eafc;
  height: 15px;
  text-align: center;
  border-radius: 50%;
  font-size: 8px;
}
.read {
  border: none;
  width: 50px;
  border-radius: 20px;
  background: #ffbb58;
}
h3 {
  font-size: 12px;
  font-weight: 600;
  color: #9dadc2;
}
p {
  font-size: 14px;
  color: #000;
  font-weight: 600;
}
.cart {
  width: 95%;
  display: flex;
  justify-content: space-between;
  height: 80vh;
}
.cart-container {
  margin-top: 20px;
  display: flex;
  flex-direction: column;
  background: #fff;
  width: 250px;
  height: 57vh;
  text-align: start;
  box-shadow: 0 3px 4px rgba(0, 0, 0, 0.2);
}
.pics {
  width: 250px;
  height: 150px;
}
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
.low-to-high:hover span,
.dropdown-relevance {
  display: block;
  cursor: pointer;
}
h5 {
  font-size: 14px;
  font-weight: 600;
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

.under-line {
  width: 170px;
  background: #9dadc2;
  height: 1.3px;
}
</style>
