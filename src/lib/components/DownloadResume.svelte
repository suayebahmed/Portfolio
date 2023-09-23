<script>
  function downloadResume() {
    const resumeUrl = '/static/resume.pdf'; 
    const link = document.createElement('a');
    link.href = resumeUrl;
    link.download = 'resume.pdf'; // Specify the desired download file name
    link.click();
  }
</script>

<style>
    button {
        margin-top: 15px;
        padding: 10px 20px;
        border-radius: 10px;
        font-family: monospace;
        border: none;
    }
</style>

<button on:click={downloadResume}>Download Resume</button>
