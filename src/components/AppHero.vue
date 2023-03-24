<template>
    <div class="wrapper">
        <div class="inner">
            <h1 class="mb-2">Vite Jumbotron</h1>
            <p class="mb-5">Lorem ipsum dolor sit amet.</p>
            <button>Hero Button</button>
        </div>
    </div>
</template>

<style scoped>
.wrapper {
    width: 100%;
    min-height: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url('/bg.png');
    background-size: cover;
}

.wrapper h1,
p {
    animation: textIn .5s ease;
}


button {
    animation: buttonIn .8s ease;
}

.mb-2 {
    margin-bottom: 5px;
}

button {
    margin: 20px 0px
}


@keyframes textIn {
    0% {
        opacity: 0;
        transform: translateY(-20px);
    }

    100% {
        opacity: 1;
        transform: translateY(0px);
    }
}

@keyframes buttonIn {
    0% {
        opacity: 0;
        transform: translateY(20px);
    }

    100% {
        opacity: 1;
        transform: translateY(0px);
    }
}
</style>

<script>

</script>