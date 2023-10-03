In this lesson we will be learning MIXIN only,

<style>
/* MIXINS -- Lesson */
@mixin btn(){
    text-decoration: none;
    cursor: pointer;
    display: inline-block;
    border: 0;
    border-radius: 5px;
    padding: 10px;
}

.btn-mixin{
    @include btn();
}
</style>