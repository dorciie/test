<template>
    <div class="container">
<form>
             <div class="form-group row" action="{{ route('login') }}">
                            <label for="email" class="col-md-4 col-form-label text-md-right">name</label>

                             <div class="col-md-6">
                                <input id="name" type="string" class="form-control" name="name" >

                               
                            </div>
                            </div>
            <div class="form-group row">
                            <label for="email" class="col-md-4 col-form-label text-md-right">email</label>

                             <div class="col-md-6">
                                <input id="email" type="email" class="form-control " name="email" >

                               
                            </div> 
                            </div>

                            <div class="form-group row">
                            <label for="password" class="col-md-4 col-form-label text-md-right">password</label>

                            <div class="col-md-6">
                                <input id="password" type="password" class="form-control " name="password" required="required">

                                
                            </div>
                        </div>

                        <div class="form-group row">
                            <div class="col-md-6 offset-md-4">
                                <div class="form-check">
                                    <input class="form-check-input" type="checkbox" name="remember" id="remember" >

                                    Remember me
                                </div>
                            </div>
                        </div>

                        <div class="form-group row mb-0">
                            <div class="col-md-8 offset-md-4">
                                <button type="submit" class="btn btn-primary">
                                    Login
                                </button>

                               
                            </div>
                        </div>

    </form>    
    
    <!-- <form > 
                        <div class="form-group row">
                            <label for="email" class="col-md-4 col-form-label text-md-right">test</label>

                             <div class="col-md-6">
                                <input id="email" type="email" class="form-control @error('email') is-invalid @enderror" name="email" >

                               
                            </div> --><!--
                        </div>

                        <div class="form-group row">
                            <label for="password" class="col-md-4 col-form-label text-md-right">{{ __('Password') }}</label>

                            <div class="col-md-6">
                                <input id="password" type="password" class="form-control @error('password') is-invalid @enderror" name="password" required autocomplete="current-password">

                                
                            </div>
                        </div>

                        <div class="form-group row">
                            <div class="col-md-6 offset-md-4">
                                <div class="form-check">
                                    <input class="form-check-input" type="checkbox" name="remember" id="remember" >

                                    <label class="form-check-label" for="remember">
                                        {{ __('Remember Me') }}
                                    </label>
                                </div>
                            </div>
                        </div>

                        <div class="form-group row mb-0">
                            <div class="col-md-8 offset-md-4">
                                <button type="submit" class="btn btn-primary">
                                    {{ __('Login') }}
                                </button>

                               
                            </div>
                        </div>
                    </form>-->
                </div>
</template>
<script>
export default {
    
}
</script>