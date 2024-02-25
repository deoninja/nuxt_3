<template>
  <div>
    <NuxtLayout>
      <header>
        <ul>
          <li>
            <NuxtLink to="/">Home</NuxtLink>
            <NuxtLink to="/events">Events</NuxtLink>
            <NuxtLink to="/events/myprofile">Profile</NuxtLink>
          </li>
        </ul>
      </header>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
