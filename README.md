<div style="text-align: center">
    <h1><u>Welcome to Hogwarts Universe!</u></h1>
    <h2><i>Welcome to the Hogwarts Universe Explore Page! Explore YOUR way through Hogwarts!</i></h2>
            <button mat-icon-button [matMenuTriggerFor]="menu" aria-label="Example icon-button with a menu">
                <mat-icon>more_vert</mat-icon>
            </button>
            <mat-menu #menu="matMenu">
                <button mat-menu-item (click)="showHome()">
                    <span>Home</span>
                </button>
                <button mat-menu-item (click)="showQuizzes()">
                    <span>Quizzes</span>
                </button>
                <button mat-menu-item disabled>
                    <span>Explore</span>
                </button>
            </mat-menu>
    <p>HOGWARTS UNIVERSE OFFICIAL LINKS:</p>
    <a href="https://docs.google.com/document/d/15sFXYNxR76AguGd_Ke5mIFSdo_QN3UC8YVyhtR0WHlw/edit?usp=sharing">Hogwarts Classes,  </a>
    <a href="https://docs.google.com/document/d/1v-rNjBDg43j0t_GBse-ZKgWBUwkods3Abb9QVoQMTng/edit?usp=sharing">The Great Hall (House Points)</a>
    <p> </p>
    <img src="../../../assets/Images/FantasyHogwarts.jpg" alt="Fantasty Image of Hogwarts School">
  <p>Offical Contact Email: seungri400@gmail.com</p>
