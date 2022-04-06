<template>
    <section class="options-prev">
    <div class="prev-card-container">
        <div class="prev-card">
            <icon-base iconName="access" />
            <h3>Access your files, anywhere</h3>
            <p>The ability to use a smartphone, tablet, 
                or computer to access your account means your files follow you everywhere.</p>
        </div>
        <div class="prev-card">
            <icon-base iconName="secure" />
            <h3>Security you can trust</h3>
            <p>2-factor authentication and user-controlled 
                encryption are just a couple of the security features we allow to help secure your files.</p>
        </div>
        <div class="prev-card">
            <icon-base iconName="collab" />
            <h3>Real-time collaboration</h3>
            <p>Securely share files and folders with friends, 
                family and colleagues for live collaboration. No email attachments required.</p>
        </div>
        <div class="prev-card">
            <icon-base iconName="store" />
            <h3>Store any type of file</h3>
            <p>Whether you're sharing holidays photos or work documents, 
                Fylo has you covered allowing for all file types to be securely stored and shared.</p>
        </div>
    </div>
    </section>
</template>

<script>
import iconBase from './icon-base.vue'
export default {
    components: { iconBase },

}
</script>

<style>
</style>