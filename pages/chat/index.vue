<template>
  <div class="flex h-screen">
    <!-- Left Sidebar -->
    <div class="w-1/4 bg-gray-900 p-4 flex flex-col">
      <div class="flex items-center space-x-2">
        <img
          class="w-10 h-10 rounded-full"
          src="@/assets/img/avatar.jfif"
          alt="Avatar"
        />
        <div class="flex-1 ml-3">
          <p class="font-bold text-white ml-3">Phạm Thanh Phương</p>
          <p class="text-sm text-gray-500 ml-3">Bạn đã gửi một ảnh - 3 phút</p>
        </div>
      </div>
    </div>

    <!-- Chat content -->
    <div class="flex-1 bg-gray-800 flex flex-col">
      <!-- Chat messages -->
      <div class="flex-1 overflow-y-auto p-4">
        <div class="space-y-4">
          <!-- Message from Phạm Thanh Phương -->
          <div class="flex items-start space-x-2">
            <img
              class="w-10 h-10 rounded-full"
              src="@/assets/img/avatar.jfif"
              alt="Avatar"
            />
            <div class="bg-gray-700 p-3 rounded-lg">
              <p class="font-semibold text-white">Phạm Thanh Phương</p>
              <img
                src="@/assets/img/avatar.jfif"
                alt="image"
                class="mt-2 rounded-lg"
              />
              <p class="text-xs text-gray-400 mt-1">Đã gửi 3 phút trước</p>
            </div>
          </div>
        </div>
      </div>

      <!-- Message input -->
      <div class="flex items-center bg-gray-700 p-3 rounded-full">
        <!-- Icon list (left side) -->
        <div class="flex space-x-2 text-black">
          <button class="w-6 h-6">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="#1e3a8a"
              class="size-6 text-black"
            >
              <path
                fill-rule="evenodd"
                d="M12 2.25c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75 9.75-4.365 9.75-9.75S17.385 2.25 12 2.25ZM12.75 9a.75.75 0 0 0-1.5 0v2.25H9a.75.75 0 0 0 0 1.5h2.25V15a.75.75 0 0 0 1.5 0v-2.25H15a.75.75 0 0 0 0-1.5h-2.25V9Z"
                clip-rule="evenodd"
              />
            </svg>
          </button>
          <button class="w-6 h-6">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="#1e3a8a"
              class="size-6"
            >
              <path
                d="M9.97.97a.75.75 0 0 1 1.06 0l3 3a.75.75 0 0 1-1.06 1.06l-1.72-1.72v3.44h-1.5V3.31L8.03 5.03a.75.75 0 0 1-1.06-1.06l3-3ZM9.75 6.75v6a.75.75 0 0 0 1.5 0v-6h3a3 3 0 0 1 3 3v7.5a3 3 0 0 1-3 3h-7.5a3 3 0 0 1-3-3v-7.5a3 3 0 0 1 3-3h3Z"
              />
              <path
                d="M7.151 21.75a2.999 2.999 0 0 0 2.599 1.5h7.5a3 3 0 0 0 3-3v-7.5c0-1.11-.603-2.08-1.5-2.599v7.099a4.5 4.5 0 0 1-4.5 4.5H7.151Z"
              />
            </svg>
          </button>
          <button class="w-6 h-6">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="#1e3a8a"
              class="size-6"
            >
              <path
                fill-rule="evenodd"
                d="M12 2.25c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75 9.75-4.365 9.75-9.75S17.385 2.25 12 2.25Zm-2.625 6c-.54 0-.828.419-.936.634a1.96 1.96 0 0 0-.189.866c0 .298.059.605.189.866.108.215.395.634.936.634.54 0 .828-.419.936-.634.13-.26.189-.568.189-.866 0-.298-.059-.605-.189-.866-.108-.215-.395-.634-.936-.634Zm4.314.634c.108-.215.395-.634.936-.634.54 0 .828.419.936.634.13.26.189.568.189.866 0 .298-.059.605-.189.866-.108.215-.395.634-.936.634-.54 0-.828-.419-.936-.634a1.96 1.96 0 0 1-.189-.866c0-.298.059-.605.189-.866Zm2.023 6.828a.75.75 0 1 0-1.06-1.06 3.75 3.75 0 0 1-5.304 0 .75.75 0 0 0-1.06 1.06 5.25 5.25 0 0 0 7.424 0Z"
                clip-rule="evenodd"
              />
            </svg>
          </button>
          <button class="w-6 h-6">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="#1e3a8a"
              class="size-6 text-white"
            >
              <path
                fill-rule="evenodd"
                d="M4.5 3.75a3 3 0 0 0-3 3v10.5a3 3 0 0 0 3 3h15a3 3 0 0 0 3-3V6.75a3 3 0 0 0-3-3h-15Zm9 4.5a.75.75 0 0 0-1.5 0v7.5a.75.75 0 0 0 1.5 0v-7.5Zm1.5 0a.75.75 0 0 1 .75-.75h3a.75.75 0 0 1 0 1.5H16.5v2.25H18a.75.75 0 0 1 0 1.5h-1.5v3a.75.75 0 0 1-1.5 0v-7.5ZM6.636 9.78c.404-.575.867-.78 1.25-.78s.846.205 1.25.78a.75.75 0 0 0 1.228-.863C9.738 8.027 8.853 7.5 7.886 7.5c-.966 0-1.852.527-2.478 1.417-.62.882-.908 2-.908 3.083 0 1.083.288 2.201.909 3.083.625.89 1.51 1.417 2.477 1.417.967 0 1.852-.527 2.478-1.417a.75.75 0 0 0 .136-.431V12a.75.75 0 0 0-.75-.75h-1.5a.75.75 0 0 0 0 1.5H9v1.648c-.37.44-.774.602-1.114.602-.383 0-.846-.205-1.25-.78C6.226 13.638 6 12.837 6 12c0-.837.226-1.638.636-2.22Z"
                clip-rule="evenodd"
              />
            </svg>
          </button>
        </div>

        <!-- Input box -->
        <input
          type="text"
          placeholder="Aa"
          class="flex-1 mx-4 bg-gray-600 text-white p-2 rounded-full focus:outline-none"
        />

        <!-- Icon list (right side) -->
        <div class="flex space-x-2 text-blue-600">
          <button class="w-6 h-6">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="#1e3a8"
              class="w-6 h-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M5 12h14M12 5l7 7-7 7"
              />
            </svg>
          </button>
          <button class="w-6 h-6">
            <img src="/assets/img/like.png" alt="Like" class="w-6 h-6" />
          </button>
        </div>
      </div>
    </div>

    <!-- Right Sidebar -->
    <div class="w-1/4 bg-gray-900 p-4 flex flex-col items-center space-y-6">
      <img
        class="w-16 h-16 rounded-full"
        src="@/assets/img/avatar.jfif"
        alt="Avatar"
      />
      <p class="font-bold text-white">Phạm Thanh Phương</p>
      <!-- Options with icons -->
      <div class="flex flex-col space-y-4 w-full mt-5">
        <!-- Icon 1: Hình tròn với dấu chấm -->
        <button
          class="bg-gray-700 px-4 py-2 rounded-lg flex items-center justify-start space-x-2 w-full hover:bg-blue-900"
        >
          <div
            class="w-5 h-5 bg-blue-900 rounded-full flex items-center justify-center"
          >
            <div class="w-2 h-2 bg-white rounded-full"></div>
          </div>
          <span class="text-white">Đổi chủ đề</span>
        </button>

        <!-- Icon 2: Like (nút với hình ảnh bạn cung cấp) -->
        <button
          class="bg-gray-700 px-4 py-2 rounded-lg flex items-center justify-start space-x-2 w-full hover:bg-blue-900"
        >
          <img src="/assets/img/like.png" alt="Like" class="w-5 h-5" />
          <span class="text-white">Thay đổi biểu tượng cảm xúc</span>
        </button>

        <!-- Icon 3: Chữ Aa -->
        <button
          class="bg-gray-700 px-4 py-2 rounded-lg flex items-center justify-start space-x-2 w-full hover:bg-blue-900"
        >
          <div class="text-blue-900 text-lg font-bold">Aa</div>
          <span class="text-white">Chỉnh sửa biệt danh</span>
        </button>
      </div>
    </div>
  </div>
</template>

<script setup>
// No additional script needed for this example
</script>

<style scoped>
/* Add custom styles if necessary */
</style>
