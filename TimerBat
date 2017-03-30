import java.io.IOException;
import java.util.Timer;
import java.util.TimerTask;
import java.util.logging.Level;
import java.util.logging.Logger;
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author andres
 */

    


public class personal {
    public static void main(String arglist[]) {
    Timer timer;
    timer = new Timer();

    TimerTask task = new TimerTask() {
        int tic=0;

        @Override
        public void run()
        {
            if (tic%2==0)
            try {
                Runtime.getRuntime().exec("cmd /c start C:\\delpersonal.bat");
            } catch (IOException ex) {
                Logger.getLogger(personal.class.getName()).log(Level.SEVERE, null, ex);
            }
            else
            try {
                Runtime.getRuntime().exec("cmd /c start C:\\delpersonal.bat");
            } catch (IOException ex) {
                Logger.getLogger(personal.class.getName()).log(Level.SEVERE, null, ex);
            }
            tic++;
        }
        };
        // Empezamos dentro de 10ms y luego lanzamos la tarea cada 1000ms
    timer.schedule(task, 10, 3600000);
    }
}
