How To Update/Add YouTube Videos
===

1. Open the `index.php` file in the `Power_On` directory of your FTP directory.

2. Look for a bunch of code blocks like the one shown below:

  ```html
  <div class="video-col">
    <h1>PROMO VIDEO</h1>
    <p>A&amp;E: The Next Duck Dynasty</p>
    <div class="videowrapper">
      <iframe
        width="560"
        height="315"
        src="//www.youtube.com/embed/CD9rtvMzJpU?rel=0&amp;autohide=1&amp;showinfo=0"
        frameborder="0"
        allowfullscreen>
      </iframe>
    </div>
  </div>
  ```
  
3. To replace one of these videos, you will need to change the text between the `<h1>` and `<p>` tags as you choose for your new video.
