package com.repputecnologia.inappwebview_fileprovider_shim

import io.flutter.embedding.engine.plugins.FlutterPlugin

class InappwebviewFileproviderShimPlugin : FlutterPlugin {
    override fun onAttachedToEngine(binding: FlutterPlugin.FlutterPluginBinding) {
        // Não faz nada em runtime. A única função deste plugin é fazer o merge do FileProvider no AndroidManifest.
    }

    override fun onDetachedFromEngine(binding: FlutterPlugin.FlutterPluginBinding) {
        // Não faz nada.
    }
}
