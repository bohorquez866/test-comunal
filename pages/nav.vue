<template>
    <header class="header">
        <nav class="nav">
        <strong>C-O-M-U-N-A-L</strong>
        </nav>
        <div class="subtitle">
<h1> {{title}}
            <br>
            <div class="section-description">
                <span>{{category}}</span> > <p> {{title}}</p>
            </div>
        </h1>
        </div>
        

    </header>
</template>

<script>
export default {
    data() {
        return {
        title: "Mis Problemas",
        category: 'Problemas'
        }
    }
}
</script>

