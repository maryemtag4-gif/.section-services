# .section-services/* --- 7. Membership/Services Section (.section-services) --- */

.section-services {
    /* Assuming this section has a clean, white/light background */
    background-color: #ffffff; 
    color: [#TEXT_COLOR_DARK]; 
    text-align: center;
    padding: [SECTION_PADDING_TOP]px 0 [SECTION_PADDING_BOTTOM]px 0; /* Adjust padding */
}

/* Optional: If there is a main heading for the membership section */
.section-services h2 {
    font-size: [H2_FONT_SIZE]px;
    margin-bottom: 50px;
}

.services-grid {
    display: grid;
    /* Often 4 columns for feature blocks, similar to the courses */
    grid-template-columns: repeat(4, 1fr); 
    gap: 30px; /* Space between the feature blocks */
    max-width: [MAX_WIDTH]px; /* Ensure content is contained */
    margin: 0 auto;
}

/* --- Individual Service Item Styling (.service-item) --- */

.service-item {
    text-align: center;
    padding: 20px;
}

.service-item img {
    /* Styling for the central icon/image */
    width: [ICON_SIZE]px; /* e.g., 60px */
    height: [ICON_SIZE]px; /* e.g., 60px */
    object-fit: contain;
    margin-bottom: 20px;
}

.service-item h3 {
    /* Title of the feature/service */
    font-size: [H3_FONT_SIZE]px;
    font-weight: 700;
    margin-bottom: 15px;
}

.service-item p {
    /* Description text */
    font-size: [P_FONT_SIZE]px;
    line-height: 1.5;
    color: [#TEXT_COLOR_SECONDARY]; /* Use a slightly lighter text color */
}
