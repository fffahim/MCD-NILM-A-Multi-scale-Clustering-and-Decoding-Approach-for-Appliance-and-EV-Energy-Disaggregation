**MCD-NILM: A Multi-scale Clustering and Decoding Approach for
Appliance and EV Energy Disaggregation**

Non-Intrusive Load Monitoring (NILM) is a promising approach for estimating individual
appliance-level energy consumption from aggregated power readings, enabling smarter resi-
dential energy management. However, most existing NILM methods rely on fixed appliance
sets, lack real-time adaptability, and often fail to accurately disaggregate complex, long-
duration loads such as electric vehicle (EV) charging, especially when these overlap with other
appliances. To address these limitations, we introduce MCD-NILM, a unified and scalable
deep learning framework that combines a shared temporal encoder, Gaussian Mixture Model
(GMM)-based soft clustering, and specialized decoders tailored to long-cycle, short-cycle,
and seasonal appliances. This architecture allows the model to dynamically route features to
appropriate decoders, capturing both appliance-specific patterns and inter-appliance interactions.
Unlike traditional appliance-specific models, MCD-NILM handles overlapping loads in a holistic
manner. We evaluate the model on public NILM datasets augmented with synthetic EV profiles
and demonstrate its superior performance in terms of Mean Absolute Error (MAE), Normalized
Disaggregation Error (NDE), and Estimated Accuracy (EAC). The results indicate that MCD-
NILM offers a scalable and generalizable solution for next-generation NILM applications,
capable of supporting smarter, more sustainable energy consumption in homes equipped with
diverse and dynamic electrical loads
