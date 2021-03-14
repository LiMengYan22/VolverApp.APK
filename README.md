# VolverApp.java
Botón para retornar la actividad o veolver atrás. Para aplicaciones móviles android (JAVA) APK..

#---en Principal.java:::
import android.view.KeyEvent;
#---y tras el primer OVERRYDE, este::
@Override
public boolean onKeyDown(int keyCode, KeyEvent event) {
WebView mWebView;
mWebView = (WebView) findViewById(R.id.webView);
if (event.getAction() == KeyEvent.ACTION_DOWN) {# VolverApp.java
