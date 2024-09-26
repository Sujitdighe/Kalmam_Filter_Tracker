Example of c calls to OpenCV's Kalman filter.
 Tracking of rotating point.
 Point moves in a circle and is characterized by a 1D state.
 state_k+1 = state_k + speed + process_noise N(0, 1e-5)
 The speed is constant.
 Both state and measurements vectors are 1D (a point angle),
 Measurement is the real state + gaussian noise N(0, 1e-1).
 The real and the measured points are connected with red line segment,
 the real and the estimated points are connected with yellow line segment,
 the real and the corrected estimated points are connected with green line segment.
 (if Kalman filter works correctly,
 the yellow segment should be shorter than the red one and
 the green segment should be shorter than the yellow one).
 Pressing any key (except ESC) will reset the tracking.
