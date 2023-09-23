<template>
  <div>
    <NuxtLayout>
      <header class="flex items-center justify-center p-3">
        <ul>
          <li>
            <NuxtLink class="mx-2" to="/">Home</NuxtLink>
            <NuxtLink class="mx-2" to="/events">Events</NuxtLink>
            <NuxtLink class="mx-2" to="/events/profile">Profile</NuxtLink>
          </li>
        </ul>
      </header>
      <NuxtPage/>
    </NuxtLayout>
  </div>
</template>
