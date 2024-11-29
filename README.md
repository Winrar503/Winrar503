Desarrollador de Software con especialización en .NET, trabajando en frontend y backend utilizando MVC y arquitectura en N-capas. Habilidades de desarrollo web con Next.js, JavaScript, y c#. Busco aplicar mis conocimientos en diferentes proyectos y colaborar con equipos de desarrollo.



## Presentación

```csharp
public class Darwin
{
    public string Nombre { get; set; }
    public string Objetivo { get; set; }
    public List<string> Tecnologias { get; set; }
    public List<string> Conocimientos { get; set; }
    public string Correo { get; set; }
    public List<string> Aptitudes { get; set; }

    public Darwin()
    {
        Nombre = "Darwin Alexis";
        Objetivo = "Ser Desarrollador .NET";
        Tecnologias = new List<string>
        {
            "C#",
            "JavaScript",
            "Bootstrap",
            "Tailwind CSS",
            "React.js",
            "Blazor",
            "ASP.NET",
            "SQL Server",
            "Git"
        };
        Conocimientos = new List<string>
        {
            "Desarrollo de aplicaciones web",
            "Frontend",
            "Backend"
        };
        Correo = "darwinvasquez611@gmail.com";
        Aptitudes = new List<string>
        {
            "Responsabilidad",
            "Desarrollo de liderazgo",
            "Programación lógica",
            "Desarrollo de software",
            "Experiencia de usuario",
            "Metodologías ágiles",
            "Proyectos de desarrollo"
        };
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        Darwin darwin = new Darwin();

        Console.WriteLine($"Nombre: {darwin.Nombre}");
        Console.WriteLine($"Objetivo: {darwin.Objetivo}");
        Console.WriteLine("Tecnologías:");
        darwin.Tecnologias.ForEach(tec => Console.WriteLine($"- {tec}"));
        Console.WriteLine("Conocimientos:");
        darwin.Conocimientos.ForEach(con => Console.WriteLine($"- {con}"));
        Console.WriteLine($"Correo: {darwin.Correo}");
        Console.WriteLine("Aptitudes:");
        darwin.Aptitudes.ForEach(apt => Console.WriteLine($"- {apt}"));
    }
}
