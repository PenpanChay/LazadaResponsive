<template>
    <div>
        <div class="bg-white">
            <div class="container">
                <nav class="navbar navbar-expand w-100">
                <img class="logo w-25" src="@/static/images/logo.png" />
                <div class="container-fluid pl-2 pr-2">
                    <div class="collapse navbar-collapse">
                    <div class="input-group mb-3">
                        <input
                        type="text"
                        class="form-control"
                        aria-label="Amount (to the nearest dollar)"
                        placeholder="Search in Lazada"
                        />
                        <div class="input-group-append">
                        <span class="input-group-text"
                            ><i class="fas fa-search"></i
                        ></span>
                        </div>
                    </div>
                    </div>
                </div>
                <div class="container-fluid pb-3 pl-2 pr-2">
                    <div class="collapse navbar-collapse">
                    <div class="row">
                        <div class="col-lg-2 col-2 sty-cart">
                        <i class="fas fa-shopping-cart"></i>
                        </div>
                        <div class="col-lg-10 col-10">
                        <img class="logo w-75" src="@/static/images/newuser.jpg" />
                        </div>
                    </div>
                    </div>
                </div>
                </nav>
            </div>
        </div>
    </div>
</template>

<style>
.input-group-text {
  color: #ffffff;
  text-align: center;
  white-space: nowrap;
  background-color: #f57224;
  border: 1px solid #f57224;
  border-radius: 0.1rem;
}
.sty-cart {
  font-size: 1.5rem;
  align-self: center;
}
</style>
