<template>
    <h1>Jobs</h1>
    <div v-for="job in jobs" :key="job.id">
        <h2>{{ job.title }}</h2>
    </div>
</template>

<script>
export default {
    data() {
        return {
            jobs: [
                { title: 'Frontend Developer', id: 1, details: 'Frontend Developer details' },
                { title: 'Backend Developer', id: 2, details: 'Backend Developer details' },
                { title: 'Fullstack Developer', id: 3, details: 'Fullstack Developer details'}
            ]
        }
    }
}
</script>

<style></style>