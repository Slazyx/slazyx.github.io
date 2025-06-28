body {
    background-image: url('font/img.png'); /* chemin vers ton image */
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-attachment: fixed;
    font-family: Arial, sans-serif;
    color: white;
    margin: 0;
    padding: 0;
  }
  
  
  .page {
    max-width: 1400px;
    margin: 0 auto;
  }
  
  .title {
    color: #01d3f8;
    font-size: 48px;
    text-align: center;
    margin-bottom: 40px;
  }
  
  .video-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 25px;
  }
  
  .video-card {
    width: 100%;
  }
  
  .thumbnail {
    position: relative;
  }
  
  .thumbnail img {
    width: 100%;
    border-radius: 10px;
  }
  
  .duration {
    position: absolute;
    bottom: 8px;
    right: 8px;
    background-color: rgba(0, 0, 0, 0.8);
    color: white;
    font-size: 12px;
    padding: 2px 5px;
    border-radius: 3px;
  }
  
  .info {
    display: flex;
    margin-top: 10px;
  }
  
  .avatar {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    margin-right: 10px;
  }
  
  .meta {
    flex: 1;
  }
  
  .meta .title {
    font-size: 15px;
    color: white;
    margin: 0;
  }
  
  .channel, .views {
    font-size: 13px;
    color: #aaa;
    margin: 2px 0;
  }
  
