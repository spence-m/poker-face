<template>
  <div class="flex items-center">
    <div class="px-8 py-6 mt-4 text-left bg-white shadow-lg">
      <div class="flex justify-center">
        <svg
          class="h-20 w-20"
          xmlns="http://www.w3.org/2000/svg"
          xml:space="preserve"
          viewBox="0 0 58.036 58.036"
        >
          <path
            fill="#efefef"
            d="m17.714 48.614 28.504 6.148a2.327 2.327 0 0 0 2.765-1.784l9-41.725a2.327 2.327 0 0 0-1.784-2.765L27.696 2.341a2.327 2.327 0 0 0-2.765 1.784l-9 41.725a2.326 2.326 0 0 0 1.783 2.764z"
          />
          <path
            fill="#e0e2e0"
            d="M17.714 48.614a2.327 2.327 0 0 1-1.784-2.765l8.374-38.824L8.497 4.837a2.327 2.327 0 0 0-2.623 1.986L.022 49.104a2.327 2.327 0 0 0 1.986 2.624l28.884 3.997a2.328 2.328 0 0 0 2.624-1.986l.231-1.667-16.033-3.458z"
          />
          <path
            fill="#c03a2b"
            d="M34.58 39.569c-5.01-5.322-7.21-9.804-8.012-12.992-.937-3.726 1.591-8.277 5.361-9.017 4.431-.87 6.691 3.28 6.691 3.28s3.77-2.849 7.448-.23c3.129 2.229 3.557 7.417 1.167 10.425-2.044 2.574-5.896 5.751-12.655 8.534z"
          />
          <path
            fill="#2c2f38"
            d="M22.218 16.701a52.951 52.951 0 0 0-1.037-.976C14.65 19.006 11.047 22.462 9.2 25.183c-2.157 3.179-1.343 8.321 1.944 10.309 3.25 1.966 6.267.072 7.146-.58l3.928-18.211z"
          />
        </svg>
      </div>
      <h3 class="text-2xl font-bold text-center">Enter room</h3>
      <form action="">
        <div class="mt-4">
          <div>
            <label class="block" for="UserName">User name</label>
            <input
              type="text"
              placeholder="UserName"
              class="w-full px-4 py-2 mt-2 border rounded-md focus:outline-none focus:ring-1 focus:ring-blue-600"
            />
            <span class="text-xs tracking-wide text-red-600"
              >User name field is required
            </span>
          </div>
          <div class="flex items-baseline justify-between">
            <button
              class="px-6 py-2 mt-4 text-white bg-blue-600 rounded-lg hover:bg-blue-900"
            >
              Login
            </button>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: 'NewSession',
  data() {
    return {}
  },

  mounted() {},
}
</script>
