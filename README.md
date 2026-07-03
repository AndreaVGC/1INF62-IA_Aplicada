1INF62-IA_APLICADA: Grupo 7

- Notebook_unificado_deforestacion_v2.ipynb: Pipeline completo sobre una AOI de Ucayali (~12,000 km²): extracción y preprocesamiento en Google Earth Engine, cálculo de índices espectrales NDVI y BSI, generación de parches con partición geográfica disjunta, y comparación entre U-Net + BCE (baseline) y Attention U-Net + BCE+Dice. Enlace colab: https://drive.google.com/file/d/1AKr_jRHCBSDugkt_e7wHx1ecUR8ueQmv/view?usp=sharing 
  
- Notebook_v4_alto_rendimiento.ipynb: Versión escalada a cuatro focos activos de deforestación (Ucayali, Madre de Dios, San Martín y Loreto) con ~7,000 parches, entrenamiento de Attention U-Net con pérdida Focal+Dice, oversampling de positivos, búsqueda de umbral óptimo y diagnóstico empírico de concordancia cross-source entre MapBiomas y Hansen GFC. https://colab.research.google.com/drive/10daHR0a11CI7TnQeoB_AtvCWSbwifsMt?usp=sharing
