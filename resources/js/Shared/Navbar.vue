<template>
    <nav class="bg-indigo-400 flex justify-evenly p-4">
        <div>
            <Link href="" class="text-xl text-white">
            Logo
            </Link>
        </div>
        <div>
            <Link href="/chat" class="text-xl text-white mr-6 hover:bg-white hover:text-indigo-400 px-4 py-2 rounded-3xl">
            Chat
            </Link>
            <Link href="/contacto" class="text-xl text-white hover:bg-white hover:text-indigo-400 px-4 py-2 rounded-3xl">
            Contacto
            </Link>
            <Link href="/nosotros" class="text-xl text-white hover:bg-white hover:text-indigo-400 px-4 py-2 rounded-3xl">
            Nosotros
            </Link>
            <Link href="/usuarios" class="text-xl text-white hover:bg-white hover:text-indigo-400 px-4 py-2 rounded-3xl">
            Usuarios
            </Link>
        </div>
    </nav>
</template>

<script>
import { Link } from "@inertiajs/vue3"
export default {
    components: {
        Link,
    }
}
</script>

<style></style>
