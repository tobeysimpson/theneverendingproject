<template>
  <Layout>
    <h1>Login</h1>
  </Layout>
</template>

<script src="https://www.gstatic.com/firebasejs/5.9.3/firebase.js"></script>
<script>
  // Initialize Firebase
  var config = {
    apiKey: "AIzaSyA8CRwDaZx_skM4ult-0VILpjph7UipIps",
    authDomain: "aesthetic-injector.firebaseapp.com",
    databaseURL: "https://aesthetic-injector.firebaseio.com",
    projectId: "aesthetic-injector",
    storageBucket: "aesthetic-injector.appspot.com",
    messagingSenderId: "799621528408"
  };
  firebase.initializeApp(config);
</script>

<script>
export default {
  metaInfo: {
    title: 'Login'
  }
}
</script>