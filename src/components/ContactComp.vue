<template>
    <div class="container mt-5 mb-5">
        <h2><i class="fa fa-contact-book"></i> Contact</h2>
        <div class="row mt-5 mb-5">
            <div class="col-sm-6 col-md-6 col-lg-6">
                <div class="card mt-5 shadow-lg">
                    <div class="card-body">
                        <div class="container">
                            <div class="row">
                                <div class="col-sm-1 col-md-1 col-lg-1">
                                    <i class="fa fa-phone"></i>
                                </div>
                                <div class="col">
                                    <p class="fst-italic">+2348131351217</p>
                                </div>
                            </div>
                            <div class="row">
                                <div class="col-sm-1 col-md-1 col-lg-1">
                                    <i class="fa fa-envelope"></i>
                                </div>
                                <div class="col">
                                    <p class="fst-italic">olubijohn4live@gmail.com</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row mt-5 mb-5">
            <div class="col-sm-6 col-md-6 col-lg-6">
                <div class="card shadow-lg">
                    <div class="card-header bg-primary text-white">
                        <p class="h3">Contact Me Now</p>
                    </div>
                    <div class="card-body btn-light">
                        <form action="">
                            <div class="mb-2">
                                <input class="form-control" type="text" name="" id="" placeholder="Full Name">
                            </div>
                            <div class="mb-2">
                                <input class="form-control" type="email" name="" id="" placeholder="Email">
                            </div>
                            <div class="mb-2">
                                <input class="form-control" type="text" name="" id="" placeholder="Message">
                            </div>
                            <div class="mb-2">
                                <input class="btn btn-primary" type="submit" name="" id="" value="Submit">
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'ContactComp'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import "@/style.css";
</style>
