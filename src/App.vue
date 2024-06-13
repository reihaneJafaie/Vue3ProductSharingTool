<script setup>
import DynamicSkeleton from "./components/DynamicSkeleton.vue";
</script>

<template>
  <section>
    <div class="card">
      <img
        src="../src/assets/reihaneJafaie.png"
        alt="Avatar"
        style="width: 100%"
      />
      <div class="textBox">
        
        <div></div>
        <h4 class="title"><b>Rei CodeBanu</b></h4>

        <div class="shareBox">
          <span
            @click="share"
            class="shareIcon "
          >
            <svg
              width="36"
              height="36"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M20.6196 13.0703C20.2396 13.0703 19.9196 12.7803 19.8696 12.4003C19.6296 10.1403 18.4096 8.09035 16.5296 6.79035C16.1896 6.55035 16.1096 6.09035 16.3396 5.75035C16.5796 5.41035 17.0496 5.33035 17.3796 5.56035C19.6196 7.11035 21.0596 9.55035 21.3496 12.2403C21.3896 12.6503 21.0996 13.0203 20.6796 13.0703C20.6696 13.0703 20.6396 13.0703 20.6196 13.0703Z"
                fill="#d87093"
              />
              <path
                d="M3.48991 13.1193C3.45991 13.1193 3.43991 13.1193 3.40991 13.1193C2.99991 13.0693 2.69991 12.6993 2.73991 12.2893C3.00991 9.59928 4.43991 7.16928 6.64991 5.59928C6.98991 5.35928 7.45991 5.43928 7.69991 5.77928C7.93991 6.11928 7.85991 6.58928 7.51991 6.82928C5.65991 8.13928 4.45991 10.1893 4.22991 12.4493C4.19991 12.8293 3.86991 13.1193 3.48991 13.1193Z"
                fill="#d87093"
              />
              <path
                d="M12.06 22.61C10.58 22.61 9.16997 22.27 7.84997 21.61C7.47997 21.42 7.32997 20.97 7.51997 20.6C7.70997 20.23 8.15997 20.08 8.52997 20.27C10.69 21.36 13.29 21.38 15.47 20.33C15.84 20.15 16.29 20.31 16.47 20.68C16.65 21.05 16.49 21.5 16.12 21.68C14.84 22.3 13.48 22.61 12.06 22.61Z"
                fill="#d87093"
              />
              <path
                d="M12.0603 8.44086C10.1103 8.44086 8.53027 6.86086 8.53027 4.91086C8.53027 2.96086 10.1103 1.38086 12.0603 1.38086C14.0103 1.38086 15.5903 2.96086 15.5903 4.91086C15.5903 6.86086 14.0003 8.44086 12.0603 8.44086ZM12.0603 2.89086C10.9403 2.89086 10.0303 3.80086 10.0303 4.92086C10.0303 6.04086 10.9403 6.95086 12.0603 6.95086C13.1803 6.95086 14.0903 6.04086 14.0903 4.92086C14.0903 3.80086 13.1703 2.89086 12.0603 2.89086Z"
                fill="#d87093"
              />
              <path
                d="M4.8298 20.6694C2.8798 20.6694 1.2998 19.0894 1.2998 17.1394C1.2998 15.1994 2.8798 13.6094 4.8298 13.6094C6.7798 13.6094 8.3598 15.1894 8.3598 17.1394C8.3598 19.0794 6.7798 20.6694 4.8298 20.6694ZM4.8298 15.1094C3.7098 15.1094 2.7998 16.0194 2.7998 17.1394C2.7998 18.2594 3.7098 19.1694 4.8298 19.1694C5.9498 19.1694 6.85981 18.2594 6.85981 17.1394C6.85981 16.0194 5.9498 15.1094 4.8298 15.1094Z"
                fill="#d87093"
              />
              <path
                d="M19.1696 20.6694C17.2196 20.6694 15.6396 19.0894 15.6396 17.1394C15.6396 15.1994 17.2196 13.6094 19.1696 13.6094C21.1196 13.6094 22.6996 15.1894 22.6996 17.1394C22.6896 19.0794 21.1096 20.6694 19.1696 20.6694ZM19.1696 15.1094C18.0496 15.1094 17.1396 16.0194 17.1396 17.1394C17.1396 18.2594 18.0496 19.1694 19.1696 19.1694C20.2896 19.1694 21.1996 18.2594 21.1996 17.1394C21.1896 16.0194 20.2896 15.1094 19.1696 15.1094Z"
                fill="#d87093"
              />
            </svg>
          </span>
          <span class="shareIcon">
            <svg
              width="36"
              height="36"
              viewBox="0 0 23 23"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M15.8926 3.15527C14.2198 3.15527 12.7226 3.96859 11.7891 5.21629C10.8556 3.96859 9.3584 3.15527 7.68555 3.15527C4.84819 3.15527 2.54688 5.46583 2.54688 8.32168C2.54688 9.4215 2.72248 10.4381 3.02747 11.3809C4.48774 16.002 8.98871 18.7654 11.2161 19.5233C11.5303 19.6342 12.0479 19.6342 12.3621 19.5233C14.5895 18.7654 19.0905 16.002 20.5507 11.3809C20.8557 10.4381 21.0313 9.4215 21.0313 8.32168C21.0313 5.46583 18.73 3.15527 15.8926 3.15527Z"
                fill="#F46B6B"
              />
            </svg>
          </span>
        </div>
        <p>
          As a professional code witch,I conjure elegant spells in the form of
          code.
        </p>
        <div>
          github: https://github.com/reihaneJafaie instagram : rei_codebanu
        </div>
        
      </div>
    </div>
  </section>
</template>
<script setup>
function share(){
  if(navigator.share){
    navigator.share({
      title: 'Reihane jafaie',
      text: 'see that Code',
      url: 'https://' + window.location.host + '/' ;
    })
  }
}

</script>

<style scoped>
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  transition: 0.3s;
  width: 310px;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  background-color: #d87093;
  border-radius: 18px;
  padding: 20px;
  margin: 0;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
}
.title {
  font-size: 32px;
  color: aliceblue;
  margin: 10px 0;
}
.textBox {
  font-size: 20px;
  margin: 0;
}

img {
  width: 100%;
  border-radius: 15px;
}
.DynamicSkeleton {
  margin: 10px auto;
}
section {
  display: flex;
  justify-content: space-around;
  gap: 20px;
}
.shareBox {
  display: flex;
  justify-content: space-between;
  gap: 12px;
  margin-top: 12px;
}
.shareIcon {
  box-shadow: 0px 4px 13px 0px #77777740;
  cursor: pointer;
  padding: 15px;
  border-radius: 10px;
  background-color: #fff;
}
</style>
