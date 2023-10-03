USING FUNCTION in SCSS

<style>

@function pixel(){
  @return 1px;
}

.using-fucntion{
    font-size: pixel();
}

</style>