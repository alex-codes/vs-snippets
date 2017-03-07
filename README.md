# vs-snippets

Basic list of Visual Studio snippets that I use day-to-day. Most snippets follow a predictable pattern for a data type and nullable data type, and others with access modifiers.

| Code | Result |
| -----| -------|
| pb   | public bool $Name$ { get; set; } |
| pbn  | public bool? $Name$ { get; set; } |
| pbg  | public bool $Name$ { get; $modifier$ set; } |
| pdt  | public DateTime $Name$ { get; set; } |
| pdtn | public DateTime? $Name$ { get; set; } |
| pdtg | public DateTime $Name$ { get; $modifier$ set; } |
| pd   | public decimal $Name$ { get; set; } |
| pdn  | public decimal? $Name$ { get; set; } |
| pdg  | public decimal $Name$ { get; $modifier$ set; } |
| pie  | public IEnumerable$T$ $Name$ { get; set; } |
| pies | public IEnumerable$SelectListItem$ $Name$ { get; set; } |
| pi   | public int $Name$ { get; set; } |
| pin  | public int? $Name$ { get; set; } |
| pig  | public int $Name$ { get; $modifier$ set; } |
| plist | public List$T$ $Name$ { get; set; } |
| ps   | public string $Name$ { get; set; } |
| psg  | public string $Name$ { get; $modifier$ set; } |
| sn   | string.IsNullOrWhiteSpace($str$) |
| pid | public int Id { get; set; } |
| pname | public string Name { get; set; } |
| pdesc | public string Description { get; set; } |

# Installation Instructions

I typically place these in \<VS-Installation-Folder\>\VC#\Snippets\1033\Custom and import them into Visual Studio (Tools -> Code Snippet Manager -> Import)
