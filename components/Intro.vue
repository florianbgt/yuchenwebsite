<template>
    <div>
        <div class="text-center">
            <nuxt-img class="img-thumbnail rounded-circle" src="Yuchen-Hua.jpg" alt="Yuchen Hua" width="250px" height="250px"/>
                <h1>Hello, I am <strong class="text-secondary">Yuchen Hua</strong></h1>
            <h2>Data Scientist | AI/ML Researcher</h2>
        </div>
        <table class="mx-auto mt-4">
            <tbody>
                <tr>
                    <td class="text-center">
                        <fa :icon="['fab', 'github']" style="font-size: 30px"/>
                    </td>
                    <td class="pl-2">
                        <big>
                            <a href="https://github.com/yuchen996" target="blank">https://github.com/yuchen996</a>
                        </big>
                    </td>
                </tr>
                <tr>
                    <td class="text-center">
                        <fa :icon="['fab', 'linkedin']" style="font-size: 30px"/>
                    </td>
                    <td class="pl-2">
                        <big>
                            <a href="https://www.linkedin.com/in/yuchen-hua-70505917b" target="blank">https://www.linkedin.com/in/yuchen-hua-70505917b</a>
                        </big>
                    </td>
                </tr>
                <tr>
                    <td class="text-center">
                        <fa :icon="['fas', 'envelope']" style="font-size: 30px"/>
                    </td>
                    <td class="pl-2">
                        <big>
                            <a href="mailto:yuchenhua96@gmail.com">yuchenhua96@gmail.com</a>
                        </big>
                    </td>
                </tr>
                <tr>
                    <td class="text-center">
                        <fa :icon="['fas', 'phone']" style="font-size: 30px"/>
                    </td>
                    <td class="pl-2">
                        <big>
                            <a href="tel:+1 413-461-8023">+1 413-461-8023</a>
                        </big>
                    </td>
                </tr>
                <tr>
                    <td class="text-center">
                        <fa :icon="['fas', 'file']" style="font-size: 30px"/>
                    </td>
                    <td class="pl-2">
                        <big>
                            <a href="/Resume-Yuchen-Hua.pdf">My PDF resume</a>
                        </big>
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
</template>