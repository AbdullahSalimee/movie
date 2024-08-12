<script>
import { page } from '$app/stores';
const movieId = $page.params.movieId;
  </script>
  
  <style>

    .container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center; /* Added to center vertically */
  height: 100vh;
  position: relative;
  overflow: hidden;
  background: 
    radial-gradient(circle, rgba(0, 0, 0, 0) 60%, rgba(0, 0, 0, 0.5) 100%), 
    url('https://image.cnbcfm.com/api/v1/image/104768589-movies-anywhere.JPG?v=1507816437&w=1920&h=1080') no-repeat center center / cover;
}
    .title {
      font-size: 70px;
      font-weight: bold;
      color: rgb(255, 255, 255);
      margin-bottom: 30px;
    }
  
    .background-image {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: inherit;
      filter: blur(20px) brightness(50%);
      z-index: -1;
    }
  
    .content {
  display: flex;
  gap: 30px;
  justify-content: center;
  margin-bottom: 90px; /* Adjust this value as needed */
}
    .button {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 300px;
      height: 150px;
      background-color: rgba(255, 0, 0, 0.563);
      color: white;
      text-align: center;
      text-decoration: none;
      font-size: 30px;
      border-radius: 10px;
      transition: all 0.3s ease;
    }
  
    .button:hover {
      background-color: rgba(0, 187, 255, 0.4);
      transform: scale(1.1);
      color: black;
    }
  </style>
  
  <div class="container">
    <div class="background-image"></div>
  
    <h1 class="title">{movieId}</h1>
  
    <div class="content">
      <a href="https://moviepire.net/" class="button" target="_blank">Watch</a>
      <a href="https://moviesmod.band/" class="button" target="_blank">Download</a>
    </div>
  </div>
  