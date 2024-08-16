# AlonsoCardenas_SOV
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com?plugins=forms,typography"></script>
    <script src="https://unpkg.com/unlazy@0.11.3/dist/unlazy.with-hashing.iife.js" defer init></script>
    <script type="text/javascript">
        window.tailwind.config = {
            darkMode: ['class'],
            theme: {
                extend: {
                    colors: {
                        border: 'hsl(var(--border))',
                        input: 'hsl(var(--input))',
                        ring: 'hsl(var(--ring))',
                        background: 'hsl(var(--background))',
                        foreground: 'hsl(var(--foreground))',
                        primary: {
                            DEFAULT: 'hsl(var(--primary))',
                            foreground: 'hsl(var(--primary-foreground))'
                        },
                        secondary: {
                            DEFAULT: 'hsl(var(--secondary))',
                            foreground: 'hsl(var(--secondary-foreground))'
                        },
                        destructive: {
                            DEFAULT: 'hsl(var(--destructive))',
                            foreground: 'hsl(var(--destructive-foreground))'
                        },
                        muted: {
                            DEFAULT: 'hsl(var(--muted))',
                            foreground: 'hsl(var(--muted-foreground))'
                        },
                        accent: {
                            DEFAULT: 'hsl(var(--accent))',
                            foreground: 'hsl(var(--accent-foreground))'
                        },
                        popover: {
                            DEFAULT: 'hsl(var(--popover))',
                            foreground: 'hsl(var(--popover-foreground))'
                        },
                        card: {
                            DEFAULT: 'hsl(var(--card))',
                            foreground: 'hsl(var(--card-foreground))'
                        },
                    },
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer base {
				:root {
					--background: 0 0% 100%;
--foreground: 240 10% 3.9%;
--card: 0 0% 100%;
--card-foreground: 240 10% 3.9%;
--popover: 0 0% 100%;
--popover-foreground: 240 10% 3.9%;
--primary: 240 5.9% 10%;
--primary-foreground: 0 0% 98%;
--secondary: 240 4.8% 95.9%;
--secondary-foreground: 240 5.9% 10%;
--muted: 240 4.8% 95.9%;
--muted-foreground: 240 3.8% 46.1%;
--accent: 240 4.8% 95.9%;
--accent-foreground: 240 5.9% 10%;
--destructive: 0 84.2% 60.2%;
--destructive-foreground: 0 0% 98%;
--border: 240 5.9% 90%;
--input: 240 5.9% 90%;
--ring: 240 5.9% 10%;
--radius: 0.5rem;
				}
				.dark {
					--background: 240 10% 3.9%;
--foreground: 0 0% 98%;
--card: 240 10% 3.9%;
--card-foreground: 0 0% 98%;
--popover: 240 10% 3.9%;
--popover-foreground: 0 0% 98%;
--primary: 0 0% 98%;
--primary-foreground: 240 5.9% 10%;
--secondary: 240 3.7% 15.9%;
--secondary-foreground: 0 0% 98%;
--muted: 240 3.7% 15.9%;
--muted-foreground: 240 5% 64.9%;
--accent: 240 3.7% 15.9%;
--accent-foreground: 0 0% 98%;
--destructive: 0 62.8% 30.6%;
--destructive-foreground: 0 0% 98%;
--border: 240 3.7% 15.9%;
--input: 240 3.7% 15.9%;
--ring: 240 4.9% 83.9%;
				}
			}
		</style>
</head>

<body>


    <div class="container mx-auto p-4">
        <header class="flex justify-between items-center mb-6">
            <div class="flex items-center">
                <h1 class="text-3xl font-bold">VALLE GRANDE</h1>
            </div>
            <nav class="space-x-4">
                <button class="bg-secondary text-secondary-foreground px-4 py-2 rounded">Nosotros</button>
                <button class="bg-secondary text-secondary-foreground px-4 py-2 rounded">Historia</button>
                <button class="bg-secondary text-secondary-foreground px-4 py-2 rounded">Video</button>
            </nav>
        </header>

        <h2 class="text-2xl font-semibold mb-4">Bienvenidos a Valle Grande</h2>

        <img src="https://vallegrande.edu.pe/wp-content/uploads/2023/11/notinov.png600x400" alt="Valle Grande Campus"
            class="w-full rounded-lg mb-4" />

        <section class="mb-6">
            <h3 class="text-xl font-bold text-red-600">Quiénes somos</h3>
            <p class="text-muted-foreground">
                Valle Grande es actualmente un Centro de Educación Superior constituido por la Promotora de Obras
                Sociales y de Instrucción Popular (PROSIP) el 25 de febrero de 1965, reconocido por el
                Ministerio de Agricultura mediante Resolución Directoral N° 04383-AG-DGAG del 2 de junio de 1983 y por
                el Ministerio de Educación mediante Resolución Ministerial N°0751-92-ED.
            </p>
        </section>

        <section>
            <h3 class="text-xl font-bold text-blue-600">Desarrollo histórico</h3>
            <p class="text-muted-foreground">Han transcurrido casi 50 años de trabajo y continuamos con el mismo deseo,
                seguir contribuyendo con el bienestar de las familias de Cañete y Yauyos.</p>
            <button class="bg-accent text-accent-foreground px-4 py-2 rounded mt-2">LEER MÁS</button>
        </section>

        <section class="mt-8 p-4 border border-muted rounded-lg">
            <h3 class="text-xl font-bold text-red-600">Misión y Visión</h3>
            <div class="mt-4">
                <h4 class="font-semibold text-brown-600">Misión</h4>
                <p class="text-muted-foreground">
                    Formar personas en el ámbito técnico profesional, considerando el sentido trascendente del hombre,
                    desarrollando en ellos competencias, que faciliten su inserción laboral, contribuyendo de
                    esta manera al desarrollo del país.
                </p>
            </div>
            <div class="mt-4">
                <h4 class="font-semibold text-brown-600">Visión</h4>
                <p class="text-muted-foreground">Ser una institución referente de excelencia de la educación técnico
                    profesional del Perú, asociada al sector productivo.</p>
            </div>
        </section>

        <footer class="mt-8 p-4 bg-blue-800 text-white rounded-lg">
            <h3 class="text-xl font-bold">Contacto</h3>
            <p class="mt-2">RUC: 20120099095</p>
            <p class="mt-1">Razón Social: I.E.S.T.P. Valle Grande</p>
            <p class="mt-1">Ant. Panamericana Sur: Km. 144,</p>
            <p class="mt-1">San Vicente de Cañete, Lima, Perú. Apartado Postal 70.</p>
            <p class="mt-2"><strong>Teléfono:</strong> (01) 581-2261</p>
            <p class="mt-1"><strong>Email:</strong> <a href="mailto:informes@vallegrande.edu.pe"
                    class="text-accent">informes@vallegrande.edu.pe</a></p>
            <p class="mt-1"><strong>Sitio web:</strong> <a href="http://www.vallegrande.edu.pe"
                    class="text-accent">www.vallegrande.edu.pe</a></p>
        </footer>
    </div>
</body>

</html>

