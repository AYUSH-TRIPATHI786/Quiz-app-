<template>
    <div>
        <b-nav tabs>
            <b-nav-item diasabled> <b>Fancy Quiz app</b></b-nav-item>
            <b-nav-item disabled> Counter: {{numCorrect}}/{{numTotal}}</b-nav-item>
         </b-nav>
    </div>
</template>

<script>
export default {
    props:[
        'numCorrect',
        'numTotal'
    ]
}
</script>