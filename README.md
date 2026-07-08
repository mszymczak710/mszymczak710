<div align="center">
  <h1>Hi, I'm Mateusz 👋</h1>

  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&pause=1000&color=2F80ED&center=true&vCenter=true&width=440&lines=Frontend+Developer;Angular+Enthusiast;Open+to+new+opportunities;Clean+Code+%26+Pixel-Perfect+UI" alt="Typing SVG" />

<br>

<a href="https://github.com/mszymczak710/mszymczak710/blob/develop/assets/Mateusz_Szymczak_CV.pdf"><img src="https://img.shields.io/badge/CV-Download-2F80ED?style=for-the-badge&logo=readdotcv&logoColor=white" alt="CV" /></a>&nbsp;&nbsp;
<a href="mailto:mszymczak710@o2.pl"><img src="https://img.shields.io/badge/Email-mszymczak710%40o2.pl-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>&nbsp;&nbsp;
<a href="https://linkedin.com/in/mszymczak710"><img src="https://img.shields.io/badge/LinkedIn-mszymczak710-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

</div>

<br>

```typescript
@Component({
  selector: 'app-mateusz',
  standalone: true,
  imports: [CommonModule],
  templateUrl: './mateusz.component.html',
  styleUrl: './mateusz.component.scss',
  changeDetection: ChangeDetectionStrategy.OnPush
})
export class Mateusz extends FrontendDeveloper implements PixelPerfectionist, TeamPlayer, ContinuousLearner {
  // --- Stack ---
  frontend: string[] = ['Angular', 'TypeScript', 'RxJS', 'NgRx', 'Signals', 'SCSS', 'Angular Material'];
  backend: string[] = ['Django REST Framework', 'PostgreSQL', 'REST APIs'];
  tools: string[] = ['Git', 'Docker', 'Jenkins', 'SonarQube', 'Postman', 'Swagger', 'Figma'];
  location: string = 'Poland 🇵🇱';

  // --- Status (reactive, of course) ---
  status = signal<string>('Open to new opportunities');
  lookingFor = signal<string[]>(['Frontend Developer', 'Angular']);

  // --- Currently leveling up ---
  learning: string[] = [
    'Master of Science in Computer Science @ WSB Merito University in Gdańsk',
    'Computer Science, spec. Web Application Development',
    'Java & Spring Boot',
    'Scalable frontend architecture'
  ];

  // --- Traits ---
  approachWork(): void {
    this.translateFigmaIntoPixelPerfectUI();
    this.writeTestsNotJustCode();
    this.keepCodeConsistent(); // built custom Prettier plugins for this
  }

  pastEpisode(): void {
    this.ledProjectBriefly(); // ERP Portal Kadrowy, before switching companies
    this.definedTasksAndEstimates();
  }

  whenIntegratingBackend(): void {
    this.mockFirst();
    this.syncWithRealAPI();
    this.testEndToEnd();
  }
}
```

<br>

<div align="center">

**Frontend**

<img src="https://skillicons.dev/icons?i=angular,ts,js,html,css,sass,jest,vitest,npm,figma" height="40" alt="Frontend technologies" />&nbsp;&nbsp;

**Backend & Data**

<img src="https://skillicons.dev/icons?i=django,postgres" height="40" alt="Backend technologies" />&nbsp;&nbsp;

**Tools & DevOps**

<img src="https://skillicons.dev/icons?i=vscode,git,github,gitlab,azure,jenkins,docker,linux,windows" height="40" alt="Tools & DevOps" />

</div>
