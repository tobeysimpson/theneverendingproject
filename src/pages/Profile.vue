<template>
  <Layout>
    <b-container fluid>
        <b-row fluid>
            <b-col style="padding-right:20px; border-right: 1px solid #ccc;">
                <b-container fluid>
                    <b-row>
                        <b-img fluid rounded="circle" src="https://picsum.photos/250/250/?image=54" alt="Image 1"></b-img>
                    </b-row>
                    <b-row>
                        <h1 class="profile-name">Lino F. Miele, MD</h1>
                    </b-row>
                    <b-row align-h="end">
                        <span class="profile-address">74 W Broad St #170 Bethlehem, PA 18018</span>
                    </b-row>
                    <b-row align-h="end">
                        <b-button variant="primary">Call Now</b-button>
                    </b-row>
                    <b-row>
                        <b-container>

                        </b-container>
                    </b-row>
                    <b-row>
                        <span>linofmielemd.com</span>
                    </b-row>
                </b-container>
            </b-col>

            <b-col>
                <h3>St. Luke’s Plastic Surgery</h3>
                <div class="--text" id="--text06">
                    <span>Dr. Miele received his medical degree from Jefferson Medical College, Thomas Jefferson University.</span>
                    <br>
                    <br>
                    <span>Following medical school, he went on to complete his residency and fellowship in Plastic, Reconstructive and Aesthetic Surgery at the University of Pittsburgh Medical Center, recognized as one of the top three plastic surgery training programs in the United States.</span>
                    <br>
                    <br>
                    <span>More than just a qualified and accomplished surgeon, 'Dr. Lino' is routinely described by his patients as a diamond in the rough.</span>
                    <br>
                    <br>
                    <span>Additionally, Dr. Miele is an active member of numerous organizations and professional societies.</span>
                    <br>
                    <br>
                    <ul>
                        <li>American Society of Plastic Surgeons</li>
                        <li>Plastic Surgery Research Council</li>
                        <li>American Society of Maxillofacial Surgery</li>
                        <li>American Society for Reconstructive Microsurgery</li>
                        <li>Robert H. Ivy Pennsylvania Plastic Surgery Society</li>
                        <li>American College of Surgeons</li>
                        <li>Association of Academic Surgeons</li>
                    </ul>
                    <br>
                    <span>A father to four beautiful daughters, Dr. Miele is widely appreciated for his genuine compassion and a traditional bedside manner seldom found in modern-day medicine.</span></div>
            </b-col>
        </b-row>
    </b-container>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Profile'
  }
}
</script>

<style>
    .profile-name {
        color: rgb(0, 0, 0);
        font-family: Montserrat, sans-serif;
        letter-spacing: -0.05rem;
        width: 100%;
        font-size: 2.125em;
        line-height: 1.125;
        font-weight: 800;

    }

    .profile-address {
        font-family: Source Sans Pro;
        margin: 0;
        padding: 0;
        border: 0;
        font-size: 100%;
        font: inherit;
        vertical-align: baseline;
    }
</style>