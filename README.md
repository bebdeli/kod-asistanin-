# kod-asistanin-BAŞLA
    ESIK = 50
    saat = 0
    
    DÖNGÜ (Sürekli / Sensör akışı boyunca)
        su_seviyesi = Sensörden_Oku()
        
        EĞER su_seviyesi > ESIK İSE
            DÖNGÜYÜ_KIR (Eşik aşıldı, döngüden çık)
        DEĞİLSE
            Kapaklar = "KAPALI"
            saat = saat + 1
        BİTİR_EĞER
    DÖNGÜ_BİTİR
    
    YAZDIR "Tahliye Saati: ", saat
    YAZDIR "Kritik Su Seviyesi: ", su_seviyesi, " metre"
    YAZDIR "Kapaklar açıldı, acil tahliye başlatıldı."
BİTİR
