const app = Vue.createApp({
    data: function () {
        return {
            tasks: [
                {
                    id: 1,
                    description: "Change the wheels",
                    situation: true
                },

                {
                    id: 2,
                    description: "Replace the turret flaire",
                    situation: false
                },

                {
                    id: 3,
                    description: "Install the Wave Radar",
                    situation: true
                },

                {
                    id: 4,
                    description: "mechanical treatment",
                    situation: true
                },
                {
                    id:5,
                    description:"hydroblasting",
                    situation: false
                },

                {
                    id:6,
                    description:"Painting",
                    situation: true
                }

            ]

        }

    }
});

app.mount("#app");
