<template>
    <div>
        <HeaderBooking></HeaderBooking>
        <main>
            <ReservationForm></ReservationForm>
        </main>
        <Footer></Footer>
    </div>
</template>

<script setup>
import HeaderBooking from '@/components/HeaderBooking.vue';
import ReservationForm from '@/components/ReservationForm.vue';
import Footer from '@/components/Footer.vue';
</script>

<style lang="scss" scoped></style>
