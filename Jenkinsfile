

stage("Start ZAP"){

    ws('workspace/zap-security-scan/build') {

        sh "/home/yelghali/Documents/ZAP_2.7.0/zap.sh –daemon -port 8070 -config api.disablekey=true -config view.mode=attack"

    }

}
