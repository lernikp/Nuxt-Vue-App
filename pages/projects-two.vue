<template>
    <div>
        <Navbar />
        <PageTitle pageTitle="Retailics" />
        <AllProjectsTwo />
    </div>
</template>

<script>
    import Navbar from '../layouts/Navbar'
    import PageTitle from '../components/Common/PageTitle'
    import AllProjectsTwo from '../components/ProjectsTwo/AllProjectsTwo'

    export default {
        components: { 
            Navbar,
            PageTitle,
            AllProjectsTwo,
        }
    }
</script>