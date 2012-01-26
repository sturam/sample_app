module ApplicationHelper

  # Return a title on a per-page basis.
  def title
    base_title = "webapp brought to by csquared.co"
    if @title.nil?
      base_title
    else
      "#{base_title} | #{@title}"
    end
  end

  def logo
	image_tag("c.png", :alt => "Sample App", :class => "round")
  end

end

