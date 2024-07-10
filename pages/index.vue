<template>
  <div class="flex h-screen max-h-screen">
    <section class="remove-scrollbar container my-auto">
      <div class="sub-container max-w-[496px]">
        <NuxtImg 
          src="/icons/logo-full.svg" 
          height="1000"
          width="1000"
          alt="patient"
          class="mb-12 h-10 w-fit"
        />

        <FormsPatientForm />

        <div class="text-14-regular mt-20 flex justify-between">
          <p class="justify-items-end text-dark-600 xl:text-left">© 2024 CarePulse</p>
          <NuxtLink to="/?admin=true" class="text-green-500">Admin</NuxtLink>
        </div>
      </div>
    </section>

    <NuxtImg 
      src="/images/onboarding-img.png"
      height="1000"
      width="1000"
      alt="patient"
      class="side-img max-w-[50%]"
    />
  </div>
</template>