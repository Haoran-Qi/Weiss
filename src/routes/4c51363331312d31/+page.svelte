<script>
	import Apollo from '../../LQ/LQ6311-1.jpg';
  import Apollo2 from '../../LQ/LQ6311-1Layout.jpg';
  import Apollo3 from '../../LQ/LQ6311-1Overall.jpg';

</script>

<style>
  main {
    display: flex;
    flex-direction: column; /* Stack children vertically */
    align-items: center;    /* Center children horizontally */
    max-height: 100vh;      /* Maximum height is the viewport height */
    overflow-y: auto;       /* Allow vertical scrolling if content overflows */
    width: 100%;            /* Take full width */
}

h1 {
    text-align: center;
    margin-bottom: 20px;
}

.image-container {
    display: flex;
    flex-direction: column; 
    align-items: center;
    width: 100%;            /* Take full width */
}

/* Style for each image */
.image-container img {
    max-width: 100%;       /* Images will not exceed the container's width */
    height: auto;          /* Adjust the height automatically based on the image's aspect ratio */
    object-fit: cover;     /* Resize the content of the image to fit its container */
    margin-bottom: 10px;   /* Margin at the bottom of each image for separation */
}
</style>
  
  <main>
    <div class="image-container">
      <img src={Apollo} alt="">
      <img src={Apollo2} alt="">
      <img src={Apollo3} alt="">
    </div>
  </main>