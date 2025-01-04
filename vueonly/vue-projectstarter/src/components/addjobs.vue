<template>
    <div class="add-jobs">
        <h1>Add a New Job</h1>
        <form @submit.prevent="submitForm">
            <div class="form-group">
                <label for="title">Job Title:</label>
                <input type="text" id="title" v-model="job.title" required />
            </div>
            <div class="form-group">
                <label for="description">Job Description:</label>
                <textarea id="description" v-model="job.description" required></textarea>
            </div>
            <div class="form-group">
                <label for="location">Location:</label>
                <input type="text" id="location" v-model="job.location" required />
            </div>
            <div class="form-group">
                <label for="salary">Salary:</label>
                <input type="number" id="salary" v-model="job.salary" required />
            </div>
            <button type="submit">Add Job</button>
        </form>
    </div>
</template>

<script>
export default {
    data() {
        return {
            job: {
                title: '',
                description: '',
                location: '',
                salary: null
            }
        };
    },
    methods: {
        submitForm() {
            // Handle form submission logic here
            console.log('Job added:', this.job);
            // Reset the form
            this.job = {
                title: '',
                description: '',
                location: '',
                salary: null
            };
        }
    }
};
</script>

<style scoped>
.add-jobs {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.form-group {
    margin-bottom: 15px;
}

label {
    display: block;
    margin-bottom: 5px;
}

input,
textarea {
    width: 100%;
    padding: 8px;
    box-sizing: border-box;
}

button {
    padding: 10px 15px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}
</style>