<template>
    <view-component :name="name" :code="code">
        <div class="py-8" slot="component">
            <div class="w-full bg-white dark:bg-gray-900">
                <div class="container flex flex-col items-center px-6 py-5 mx-auto space-y-6 sm:flex-row sm:justify-between sm:space-y-0 ">
                    <div class="-mx-2">
                        <a href="#" class="inline-flex items-center justify-center px-4 py-1 mx-2 text-gray-700 transition-colors duration-200 transform bg-gray-100 rounded-lg dark:text-white dark:bg-gray-700">
                            1
                        </a>

                        <a href="#" class="inline-flex items-center justify-center px-4 py-1 mx-2 text-gray-700 transition-colors duration-200 transform rounded-lg hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700">
                            2
                        </a>

                        <a href="#" class="inline-flex items-center justify-center px-4 py-1 mx-2 text-gray-700 transition-colors duration-200 transform rounded-lg hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700">
                            3
                        </a>
                    </div>

                    <div class="text-gray-500 dark:text-gray-400">
                        <span class="font-medium text-gray-700 dark:text-gray-100">1 - 25</span> of 77 records
                    </div>
                </div>
            </div>
        </div>
    </view-component>
</template>

<script>
export default {
    data() {
        return {
            name: 'Table',
            code: `
        <div class="w-full bg-white dark:bg-gray-800">
            <div class="container flex flex-col items-center px-6 py-5 mx-auto space-y-6 sm:flex-row sm:justify-between sm:space-y-0 ">
                <div class="-mx-2">
                    <a href="#" class="inline-flex items-center justify-center px-4 py-1 mx-2 text-gray-700 transition-colors duration-200 transform bg-gray-100 rounded-lg dark:text-white dark:bg-gray-700">
                        1
                    </a>

                    <a href="#" class="inline-flex items-center justify-center px-4 py-1 mx-2 text-gray-700 transition-colors duration-200 transform rounded-lg hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700">
                        2
                    </a>

                    <a href="#" class="inline-flex items-center justify-center px-4 py-1 mx-2 text-gray-700 transition-colors duration-200 transform rounded-lg hover:bg-gray-100 dark:text-white dark:hover:bg-gray-700">
                        3
                    </a>
                </div>

                <div class="text-gray-500 dark:text-gray-400">
                    <span class="font-medium text-gray-700 dark:text-gray-100">1 - 25</span> of 77 records
                </div>
            </div>
        </div>`
        }
    }
}
</script>